# OverTheWire Bandit - Level 1 to Level 2

## Objective

The objective of this challenge is to find the password for the next level by reading a file with a special filename.

## Step 1 - List the Files

After logging in to the Bandit Level 1 account, I used the `ls` command:

```bash
ls
The command showed a file named:

-
Step 2 - Read the File

The filename is -, which can be interpreted by Linux commands as an option.

To read the file correctly, I used:

cat ./-
The ./ tells Linux that - is a file in the current directory.

The file contained the password required for the next level.

Commands Learned
ls
ls
Used to list files and directories.

cat
cat ./-

Used to display the contents of the file named -.

./
./

Used to specify that a file or directory is located in the current directory.

What I Learned
How to work with files having special names.
Why - can be treated as an option by Linux commands.
How to use ./ to specify a file in the current directory.
How to read files using the Linux terminal.
Result

I successfully completed Bandit Level 1 → Level 2 and obtained the password needed for the next level.

Next

Bandit Level 2 → Level 3


Paste this into:

```text
Level-01-to-Level-02/README.md
