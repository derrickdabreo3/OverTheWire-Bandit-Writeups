# Level 2

## Goal

Retrieve the password for Level 3 from the file named `-` located in the home directory.

---

## Access

The connection was established using SSH with the credentials obtained from Level 1.

For SSH setup instructions, refer to the [PuTTY Setup Guide](../Setup/PuTTY-Setup/README.md).

---

## Credentials

### Username

```text
bandit1
```

### Password

```text
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

---

## Commands Used

### Command 1 — List Files and Directories Using `ls -la`

```bash
ls -la
```

Lists all files and directories, including hidden files, along with detailed file permissions and ownership information.

### Command 2 — Read File Contents Using `cat`

```bash
cat ./-
```

Displays the contents of the file named `-`.

---

## Explanation

The `ls -la` command was used to identify the file named `-` in the home directory.

The `cat ./-` command displayed the contents of the file named `-`.

The `./` prefix is required because the `-` character is normally interpreted as standard input/output by Linux commands.

Using `./` forces Linux to treat `-` as a filename located in the current directory.

---

## Retrieved Password

```text
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

---

## Screenshots

### SSH Login

![SSH Login](Screenshots/1-level2-ssh-login.png)

### Password Retrieval from `-`

![Password Retrieval](Screenshots/2-level2-password-retrieval.png)

---

## Key Learning

- Understanding special filenames in Linux
- Reading files with special characters
- Using relative paths
- Understanding Linux command-line parsing behavior
