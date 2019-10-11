Reducers
========

---

## Two Types of Reducers

@snap[west span-45]
### @size[40px](Entity Reducers)

```javascript
{
  id1: { ... },
  id2: { ... }
}
```

@size[22px](The state in these reducers act like a key-value dictionary. The reducer function, itself, only works to add, 
remove, or modify the entries of the dictionary.)
@snapend

@snap[east span-45]
### @size[40px](Domain-Specific Reducers)

@size[22px](These are organized in a way that makes sense for your app. Common ways of grouping include by page/view or by 
overarching features.)
@snapend
