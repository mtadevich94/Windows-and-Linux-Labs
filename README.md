# AegisShield Labs

Hands-on labs that pair with the [Project AegisShield](https://projectaegisshield.com) roadmap. Each lab gives you a short set of instructions and a script that spins up a VM, so you can practice a skill instead of just reading about it.

## How to use these labs

1. Clone this repo (or just download the folder for the lab you want).
2. Open the lab's own `README.md` and follow it top to bottom — prerequisites, setup, tasks, and cleanup.
3. **Read the setup script before you run it.** Every lab's script is plain text in this repo — open it, skim it, know what it's about to do on your machine before you execute it. That habit is worth building on day one.
4. When you're done, follow the lab's cleanup/teardown steps. Don't leave a VM running that you don't need.

## Lab index

| Lab | Topic | OS | Difficulty | Est. Time |
|---|---|---|---|---|
| [01-windows-navigation](labs/01-windows-navigation/) | Navigating and searching the filesystem | Windows | Beginner | 30–45 min |
| [02-linux-navigation](labs/02-linux-navigation/) | Navigating and searching the filesystem | Linux | Beginner | 30–45 min |

## Safety notice

These scripts are meant to run inside a disposable VM or sandbox, not on a machine you care about. Before running anything here:

- Review the script yourself first — don't run something you haven't read.
- Use an isolated environment (a local VM via VirtualBox/Vagrant/Hyper-V, or a throwaway cloud instance).
- If a lab spins up a cloud VM, follow its cleanup steps when you're finished — an instance left running is a bill nobody wants.
- These labs are for learning. They are not hardened for production use and shouldn't be pointed at anything sensitive.

## Versioning

The main [AegisShield site](https://projectaegisshield.com) links to a **tagged release** of this repo, not the `main` branch — so a lab you find from the site today will still work the same way months from now, even as new labs get added or old ones get revised on `main`.

## Contributing

Found a bug in a lab, or want to suggest a new one? Open an issue using the templates in `.github/`. Pull requests are welcome — see the PR template for what to include.
