```less
/* always in every file of styles*/
:host {
    display: block;

    /* host modifficator */
	&._short {
		table {
			border-spacing: 0px 8px;
		}
	}
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

/* element/block */
table {
	border-spacing: 0px 10px;
}
```
