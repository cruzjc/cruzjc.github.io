---
layout: post
---

# Unity notes
## Quaterion.identity
No rotation
https://docs.unity3d.com/ScriptReference/Quaternion-identity.html


## Usefull for pausing game
```C# Unity

>    bool IsPlayerEngaged()
>    {
>        bool outOfBoundsA=Input.mousePosition.x<=0||Input.mousePosition.y<=0;
>        bool outOfBoundsB = Input.mousePosition.x >= Screen.width-2 || Input.mousePosition.y >= Screen.height-2;
>        if(outOfBoundsA||outOfBoundsB){
>            return false;
>        }
>        return true;
>    }

```

>    private void OnMouseOver()
>    {
>        if (Input.GetMouseButtonDown(0))
>        {
>            Destroy(gameObject);
>        }
>    }
