# labels
This repo contains the default labels I use in ym repositories.

You can use the [`labels.yaml`](./labels.yaml) file along with my [`EndBug/label-sync`](https://github.com/EndBug/label-sync) action to copy them to your repo: you can tweak the aliases so that you don't loose your current tags, but they only get edited.

If you're creating a brand new repository, you can just use this as your `source-repo` parameter for the action: it will copy over all the labels. You can also use the `delete-other-labels` parameter to make it delete any additional labels.
