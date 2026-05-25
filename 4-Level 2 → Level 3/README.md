# Level 3

## Goal

Retrieve the password for Level 4 from the file named `--spaces in this filename--` located in the home directory.

---

## Access

The connection was established using SSH with the credentials obtained from Level 2.

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

Lists all files and directories, including hidden files, along with detailed file permissions and ownership information.

### Command 2 — Read File Contents from a Filename Containing Spaces Using `cat`

```bash
cat "./--spaces in this filename--"
```

Displays the contents of the file named `--spaces in this filename--`.

---

## Explanation

The `ls -la` command was used to identify the file named `--spaces in this filename--` in the home directory.

The `cat` command was used to display the contents of the file.

Double quotation marks were required because the filename contains spaces and must be treated as a single argument.

The `./` prefix forces Linux to treat the filename as a file located in the current directory.

Without quotation marks, Linux would interpret each word separated by spaces as a separate argument.

---

## Retrieved Password

```text
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

---

## Screenshots

### SSH Login

![SSH Login](screenshots/1-level3-ssh-login.png)

### Password Retrieval from Filename Containing Spaces

![Password Retrieval](screenshots/2-level3-password-retrieval.png)

---

## Key Learning

- Handling filenames containing spaces in Linux
- Using quotation marks in shell commands
- Understanding Linux argument parsing
- Reading files with special filenames
