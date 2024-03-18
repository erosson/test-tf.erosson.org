Deploy the contents of `/release` to any static site webhost. No additional build step required - this branch is a snapshot of the `main` branch's latest build output.

_Why?_ This branch decouples build/CI from webhosting/deployment. It's much easier to switch webhosts later!

Created using https://github.com/erosson/infra/blob/main/tf/modules/git-release-branch

    bash ./public main.release
