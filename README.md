# ARSupportChecker

#Installation


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
