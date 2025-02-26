# obisdian-notion-toggle-list 🪨
A workaround for getting notion-style toggle lists in [Obsidian](https://obsidian.md/) using custom callouts:

![image](https://github.com/user-attachments/assets/422bdcdf-8750-43aa-bdb2-14586d49db82)

## Setup

1. Go to `⚙️` > `Appearance` > `CSS snippets` and add a `minimal-collapse` CSS file.
2. Copy the content from `snippets/minimal-collapse.css` into that file and enable it.

## Usage

Simply use it like this:

```md
> [!collapse]- Port usage of [[Kerberos]] and [[NTLM]]
> Older version used [[NTLM]] as a protocol instead of [[Kerberos]]. Both require
> that certain ports have to be open on the network and all the users, computers,
> and resources be registered with that central authority.
```
