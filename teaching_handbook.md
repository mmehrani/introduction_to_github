# Teaching Assisstant

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
### To produce type 1:
Ask the *Assisstant* to put `'Ciao'` instead and then commit it.
```
print(name+'Ciao!')
```
Afterward without `pull` change the indicated to `'Hola!'` and try to commit and push it!

```
print(name+'Hola!')
```
**Congratulations! Conflict is made!**

### To produce type 2:

**Congratulations! Conflict is made!**

### To produce type 3:
**Congratulations! Conflict is made!**
