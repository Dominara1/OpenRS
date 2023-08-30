# OpenRS

OpenRC rewrite in Rust.

# [](https://github.com/Dominara1/OpenRS/tree/main#what-will-this-do)What will this do?

Simple, it'll be designed to replace the horrendous init system OpenRC with something far simpler, quicker, & all around better to use. I aim to make it compatible with old OpenRC scripts, but if I find they're too annoying to deal with. I'll deal away with that idea.

# [](https://github.com/Dominara1/OpenRS/tree/main#design-philosophy)Design philosophy

I plan on having a simple ordinance system as follows: 0 -> As soon as the init starts up, 1 is a bit after that, 2 is before login, 3 is when you've logged in, 4 will be userspace.

0 -> boot 
1 -> midboot 
2 -> prelogin 
3 -> onlogin 
4 -> userspace
