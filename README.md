# treenode-widget
## Debut idea
The tn_parent field of the administrator's form [django-treenode](https://github.com/fabiocaccamo/django-treenode)is very inconvenient to use. This widget allows you to search and presents related items in the form of a tree.

## Install
Download and extract the files to your application folder using django-treenode

## Usage

```
class YoursForm(TreeNodeForm):

    class Meta:
        widgets = {
            'tn_parent': TreeWidget(attrs={'style': 'min-width:400px'}),
        }
```

## Credits
This software contains, uses, including in a modified form:
*  [Select2-to-Tree](https://github.com/clivezhg/select2-to-tree) Select2 extension by [clivezhg](https://github.com/clivezhg)
