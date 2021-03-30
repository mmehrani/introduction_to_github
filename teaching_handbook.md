# Teaching Assistant

## An example for introducing basic commands
Start with this code:
```
def farewell():
    print('Hello!')
    return
```
Try to add `name` in the argument and then commit it.
```
def farewell(name):
    print(name + 'Hello!')
    return
```
## Conflicts
Ask the *Assisstant* to put `'Ciao'` instead and then commit it.
```
print(name+'Ciao!')
```
Afterward without `pull` change the indicated to `'Hola!'` and try to commit and push it!

```
print(name+'Hola!')
```
**Congratulations! Conflict is made!**
