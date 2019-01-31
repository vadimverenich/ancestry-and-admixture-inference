# Global ancestry models for worldwide human population

## Description
The collection holds various models of global worldwide ancestry (with the number of ancestral components ranging from K=6 up to K=28), which can be easily integrated into separate project as pre-maid reference panels for iAdmix, SNPWEIGHTS, fastNGSadmix 


```flow
st=>start: Login
op=>operation: Login operation
cond=>condition: Successful Yes or No?
e=>end: To admin

st->op->cond
cond(yes)->e
cond(no)->op
