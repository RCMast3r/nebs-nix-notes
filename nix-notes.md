a kind of hacky way to see if you are in a nix shell is to echo the $PATH and see if there are any nix store paths within it.

opengl stuff within nix can be weird, especially in non-NixOS environments and google has a hard time finding the solutions that the nix wiki has for 

"Error: couldn't find RGB GLX visual or fbconfig"

https://nixos.wiki/wiki/Nixpkgs_with_OpenGL_on_non-NixOS can provide the solution

`nixGL` has worked for me, however getting the built in nvidia graphics card has been a challenge on wsl2 and currently does not work correctly...


links to blogs / resources:
https://ianthehenry.com/posts/how-to-learn-nix/introduction/
https://serokell.io/blog/practical-nix-flakes
