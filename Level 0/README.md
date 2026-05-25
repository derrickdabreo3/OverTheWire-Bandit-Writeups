# Level 0

## Goal

Log in to the Bandit server using SSH and retrieve the password required for Level 1.

---

## Access

The connection was established using the saved PuTTY session configured earlier.

For SSH setup instructions, refer to the [PuTTY Setup Guide](../Setup/PuTTY-Setup/README.md).

---

## Credentials

### Username

```text
bandit0
```

### Password

```text
bandit0
```

---

## Commands Used

### Command 1 — List Files and Directories Using `ls -la`

```bash
ls -la
```

### Command 2 — Read File Contents Using `cat`

```bash
cat readme
```

---

## Explanation

The `ls -la` command lists all files and directories, including hidden files, along with detailed file permissions and ownership information.

The `cat readme` command displays the contents of the `readme` file, which contains the password required to access Level 1.

---

## Retrieved Password

```text
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

---

## Screenshots

### SSH Login

![SSH Login](screenshots/level0-ssh-login.png)

### Password Retrieval

![Password Retrieval](screenshots/level0-password-retrieval.png)

---

## Key Learning

- Understanding SSH authentication
- Connecting to remote Linux systems
- Using PuTTY sessions
- Basic Linux command execution
