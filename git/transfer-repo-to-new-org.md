# Title

### Backstory

My work has a situation where some web properties were developed by a third party, but now they're being brought in house. When the time is right, that means moving it from their GitHub organization to our newly created one. 

The key is this: The person doing the transferring must have owner credentials on the new org. From there, it's a breeze. From the official GitHub docs:

1. On GitHub, navigate to the main page of the repository.
2. Repository settings buttonUnder your repository name, click **Settings**.
3. Click **Transfer**.
4. Read the warnings and enter the repository name to confirm that you've done so.
5. Type the name of the new owner and click **I understand, transfer this repo**.

Caveat: You must have admin (or owner) right on both the sending and receiving orgs. This only makes sense to protect repos from being unduly moved.

#### Reference

[Transferring a repository](https://help.github.com/articles/transferring-a-repository/)
