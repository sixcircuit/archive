# Archive
Scripts for archiving and mouting digital media

`rip <directory_name>` disk dumps, sha1s, gzips, and verifies `/dev/cdrom` to `directory_name`. `directory_name` will be created.

`mnt <directory_name>` verifies and mounts an image created with `rip`. It unzips the image to a temporary file, verifies it, opens a shell, and mounts the image. when you exit, it cleans up after itself.
