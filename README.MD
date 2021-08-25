```less
/* always in every file of styles*/
:host {
    display: block;
}

/* element/block */
.action{
   /* sub elements */
   &-content{}
   &-icon{
      /* modifficators */
      &_size{
         /* modifficator value */
         &_m{
         }
      }
      &_hidden{}
   }
}
```