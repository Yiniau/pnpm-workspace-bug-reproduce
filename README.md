# pnpm-workspace-bug-reproduce

command `pnpm i` never installs dependencies to the package `project-excluded` even in its own directory.

only execute `pnpm i --filter <package name>` could work(in its own directory).
