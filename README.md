# foundations-data
Block store for foundations project. Every commit to the ```{insert session name here}``` branch should be all the new blocks for the latest transaction on that sesssion. Note: if you merge a session and you want the blocks then you need to include the root commit to avoid the session blocks being GC'd.

Idea is that each foundations user should probably create their own foundations-data repo that they can then point to for the blocks they want to publish. They may also want to create a private version if they have private data they want to store.
