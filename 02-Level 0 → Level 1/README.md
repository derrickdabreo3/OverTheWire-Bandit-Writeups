# Level 1

## Goal

Retrieve the password for Level 2 from the `readme` file located in the home directory.

---

## Access

The connection was established using SSH with the credentials obtained from Level 0.

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

Lists all files and directories, including hidden files, along with detailed file permissions and ownership information.

### Command 2 — Read File Contents Using `cat`

```bash
cat readme
```

Displays the contents of the `readme` file.

---

## Explanation

The `ls -la` command was used to identify the `readme` file in the home directory.

The `cat readme` command displayed the contents of the `readme` file, which contained the password required to access Level 2.

---

## Retrieved Password

```text
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

---

## Screenshots

### Password Retrieval from `readme`

![Password Retrieval](screenshots/1-level1-password-retrieval.png)

---

## Key Learning

- Using SSH credentials to access remote systems
- Listing files in Linux using `ls -la`
- Reading file contents using `cat`
- Understanding Linux file permissions and directory listings
