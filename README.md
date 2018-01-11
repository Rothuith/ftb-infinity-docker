# FTB Infinity

For instructions on how to use this docker image, see [dlord/minecraft][].

To download this docker image, use this command:

> docker build github.com/Rothuith/ftb-infinity-docker

Afterwards acquire the container image ID once it's build, and use this command to run the container:

> docker run \
    --name minecraft-instance \
    -p 0.0.0.0:25565:25565 \
    -d \
    -it \
    -e DEFAULT_OP=insertyourminecraftuserhere \
    -e MINECRAFT_EULA=true \
    insert container image ID here



## Pull Request Guidelines

All pull requests must have a description, and commit messages must follow
the Linux Kernel standards. Please see [Care And Operation Of Your Linus Torvalds][]
or [How to Write a Git Commit Message][] by Chris Beams.


[Care And Operation Of Your Linus Torvalds]: https://www.kernel.org/doc/Documentation/SubmittingPatches
[How to Write a Git Commit Message]: http://chris.beams.io/posts/git-commit/

[dlord/minecraft]: https://hub.docker.com/r/dlord/minecraft/
