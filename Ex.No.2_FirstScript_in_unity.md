# Ex.No: 2  Welcome Script in Unity
### DATE:28-04-2026                                                                         
### REGISTER NUMBER : 212223240172
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using UnityEngine;

public class firstscript : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    public Transform object1;
    public float speed ;
    void Start()
    {
        //print("Welcome to Unity!");
    }

    // Update is called once per frame
    void Update()
    {
        //print("Welcome to Unity!");
        //this.transform.Translate(0.02f, 0, 0);
        //transform.position += new Vector3(0.02f, 0, 0);
        if(Input.GetKeyDown(KeyCode.Space))
        {
            object1.position += new Vector3(0, 0, speed);
        }
    }
}
```
### Output:

<img width="1600" height="833" alt="WhatsApp Image 2026-04-28 at 11 06 29 PM" src="https://github.com/user-attachments/assets/a91e5672-72be-4ac5-bbed-066ffe8c1609" />


### Result:
Thus the welcome script was printed on Console Window  sucessfully.

