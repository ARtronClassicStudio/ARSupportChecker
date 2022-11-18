# ARSupportChecker

# Installation
Copy 
~~
~~
and paste to 

![image](https://user-images.githubusercontent.com/68843488/202701019-00299f7b-d4f8-40e0-8530-2ec4d226bfe5.png)



```C#
using UnityEngine;
using ARSupportCheck;
public class Sample : MonoBehaviour
{
    public GameObject canvas;

    private void Start()
    {
        if (ARSupportChecker.IsSupported)
        {
            //NO ARCore
            canvas.SetActive(true);
        }
        else
        {
            //YSE ARCore
            canvas.SetActive(false);
        }
    }
}
```
