# Level 2

## Goal

Retrieve the password for Level 3 from the file named `--spaces in this filename--` located in the home directory.

---

## Access

The connection was established using SSH with the credentials obtained from Level 1.

For SSH setup instructions, refer to the [PuTTY Setup Guide](../Setup/PuTTY-Setup/README.md).

---

## Credentials

### Username

```text
bandit2
```

### Password

```text
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

---

## Commands Used

### Command 1 — List Files and Directories Using `ls -la`

```bash
ls -la
```

### Command 2 — Read File Contents with Spaces in Filename

```bash
cat -- "--spaces in this filename--"
```

---

## Explanation

The `ls -la` command was used to identify the file named `--spaces in this filename--` in the home directory.

The `cat` command was used to display the contents of the file.

Double quotes were required because the filename contains spaces. The `./` prefix ensures the filename is treated as a local file path.

---

## Retrieved Password

```text
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

---

## Screenshots

### SSH Login

![SSH Login](screenshots/1-level2-ssh-login.png)

### Password Retrieval

![Password Retrieval](screenshots/2-level2-password-retrieval.png)

---

## Key Learning

- Handling filenames containing spaces
- Using quotation marks in Linux commands
- Understanding shell argument parsing
- Reading files with special filenames
