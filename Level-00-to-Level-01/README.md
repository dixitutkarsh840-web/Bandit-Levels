# OverTheWire Bandit - Level 0 to Level 1

## Objective

The objective of this challenge is to connect to the Bandit server using SSH and find the password for the next level.

## Step 1 - Connect to the Server

I connected to the Bandit server using SSH.

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

The username is:

```text
bandit0
```

The SSH port is:

```text
2220
```

## Step 2 - List the Files

After logging in, I used the `ls` command:

```bash
ls
```

The command showed a file named:

```text
readme
```

## Step 3 - Read the File

I used the `cat` command:

```bash
cat readme
```

The `readme` file contained the password required for the next level.

## Commands Learned

### SSH

```bash
ssh username@hostname -p port
```

Used to connect to a remote computer securely.

### ls

```bash
ls
```

Used to list files and directories.

### cat

```bash
cat filename
```

Used to display the contents of a file.

## What I Learned

* How to connect to a remote Linux server using SSH.
* How to use a custom SSH port.
* How to list files using `ls`.
* How to read files using `cat`.
* Basic Linux command-line usage.

## Result

I successfully completed **Bandit Level 0 → Level 1** and obtained the password needed for the next level.

## Next

**Bandit Level 1 → Level 2**
