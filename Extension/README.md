# Extension

> For now this example only works in command line mode.
> Extension feature is current in beta.

This example demonstrates how to use ananas extension in an Ananas project. Currently it does not works from Ananas Deskopt. You need to use Ananas CLI to try it.

All commands in this doc are executed from current example directory.

`extension.yml` file defines all extensions required by this project. You can install other extensions with following command:

```
ananas extension install [extension url]@[version]
```

To run the example, run command:

```
ananas run number_view
```
It tells Ananas to run the step with id `number_view`.

If everything goes well, you will see following output:

```
{
  "code" : 200,
  "data" : {
    "jobid" : "0f3d0620-7b40-43c9-9c59-87bf3ba6ec4d"
  }
}
```

The job id should be different from the above one. 

You can find a new directory `extensions` created with the required extensions installed in it.

To see the result run command `view`:

```
ananas view 0f3d0620-7b40-43c9-9c59-87bf3ba6ec4d number_view -q "SELECT RATE FROM PCOLLECTION"
```





