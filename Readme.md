
### Repro steps

```
git clone https://github.com/tconn89/ReproConstrictedButton

touch .npmrc

# fill in the .npmrc 

yarn install

yarn android

```

### Notes

You will receive an error related to this import 

`import ConstrictedButton from '@bit/linos.design-system.constricted-button';`  


Feel free to uncomment that line above to see the app working as normal.
