# pixi-pylance-test

Reproducible example of pixi editable not working with pylance.

## Prerequisites:

- VSCode with python and pylance installed
- Pixi installed


To use :
Clone the repo :
```
git clone https://github.com/clement-chaneching/pixi-pylance-test.git
```

In test1 folder, run:
```
pixi install
```

In VSCode, when exploring test1/test1/test1.py you shouldnt be able to navigate to test2 with pylance.

## Remarks

As mentioned in the open bug : 
- it works with test2 is not "editable"
- Adding pip, running pixi shell and trying to use `pip install -e ../test2` doest not solve this issue 