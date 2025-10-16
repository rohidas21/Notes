my notes

# Unity3d / C\# Useful links

![][image1]

## SECTION: Photon

## Photon Supported Types

[Serialization in Photon](https://doc.photonengine.com/pun/current/reference/serialization-in-photon)

#### *Reconnect example* *RecoverFromUnexpectedDisconnectSample*

[Analyzing Disconnects | Photon Engine](https://doc.photonengine.com/pun/current/troubleshooting/analyzing-disconnects#send_less)

#### *Disabling Timeouts For Debugging*

[Debugging | Photon Engine](https://doc.photonengine.com/server/current/operations/debugging)

## [Quill18's Unity 3d & Blender Game Programming Tutorials](http://quill18.com/unity_tutorials/)

## SECTION: C\# .Net

#### *Intro to Console app*

[Discover C\# Project Types](https://www.csharpprojects.com/)  
[Intro to Console Apps in C\# in .NET 6](https://www.youtube.com/watch?v=8bOoiftm5wM&ab_channel=IAmTimCorey)

#### [*https://www.csharpprojects.com/*](https://www.csharpprojects.com/)

[Intro to Windows Forms (WinForms) in .NET 6](https://youtube.com/watch?v=0zLZQesgV5o&ab_channel=IAmTimCorey)

#### 

#### *Intro to Universal Windows Platform (UWP) Apps in C\#*

[Intro to Windows Forms (WinForms) in .NET 6](https://www.youtube.com/watch?v=0zLZQesgV5o&ab_channel=IAmTimCorey)

#### *Convert string to float with decimal values*

 float value \= float.Parse(value2.ToString("0.0"));  
float value \= float.Parse(string.Format("0.0", value2));

#### *Abstract class vs. Interface*

[When to use an abstract class vs. interface in C\# | InfoWorld](https://www.infoworld.com/article/2242358/when-to-use-an-abstract-class-vs-interface-in-csharp.html)

## SECTION: PENPOT

#### *SVG Tutorial*

[SVG: Scalable Vector Graphics | MDN](https://developer.mozilla.org/en-US/docs/Web/SVG)

#### *SVG Formatter*

[SVG Formatter and Beautifier online](https://codebeautify.org/svg-formatter-beautifier)

#### *UXML Intro*

[Manual: Introduction to UXML](https://docs.unity3d.com/Manual/UIE-WritingUXMLTemplate.html)

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

## SECTION: .Net InputSimulator Plugin

[GitHub \- michaelnoonan/inputsimulator: Windows Input Simulator (C\# SendInput Wrapper \- Simulate Keyboard and Mouse)](https://github.com/michaelnoonan/inputsimulator)

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

## SECTION: UNITY3D

### **TextMeshProUGUI: Overflow scrolling / Page Show NextPage**

[TextMesh Pro - Text Overflow Page Mode](https://www.youtube.com/watch?v=cuW0gWk2dAk&ab_channel=Zolran)

### **Rebuild Layout and Force Update Immediate**

        gameObject.SetActive(\!gameObject.activeSelf);  
        gameObject.SetActive(\!gameObject.activeSelf);  
        Canvas.ForceUpdateCanvases();

        LayoutRebuilder.MarkLayoutForRebuild(\_rightPanel);  
        LayoutRebuilder.MarkLayoutForRebuild(\_leftPanel);  
        LayoutRebuilder.ForceRebuildLayoutImmediate(\_masterPanel);  
        SceneView.RepaintAll();

horizLayoutGroup.CalculateLayoutInputHorizontal();  
horizLayoutGroup.CalculateLayoutInputVertical();  
horizLayoutGroup.SetLayoutHorizontal();  
horizLayoutGroup.SetLayoutVertical();

### **How To Get A Better Grid Layout in Unity**

[How To Get A Better Grid Layout in Unity](https://www.youtube.com/watch?v=CGsEJToeXmA&ab_channel=GameDevGuide)

### **Unity Font Asset: Dingbats, Utf codes, multiple font styles, Materials**

[TextMesh Pro - Multi Fonts & Sprite with Font Awesome](https://www.youtube.com/watch?v=0w827VBocIY&ab_channel=Zolran)  
[TextMesh Pro - Working with Material Presets](https://www.youtube.com/watch?v=d2MARbDNeaA&ab_channel=Zolran)  
[TextMesh Pro - Font Asset Creation](https://www.youtube.com/watch?v=qzJNIGCFFtY&ab_channel=Zolran)  
[TextMesh Pro - Font Fallback Overview](https://www.youtube.com/watch?v=K1Cj16TB1l0&ab_channel=Zolran)

### **Unity Remote Android/Ios Debugging Application**

[Unity Remote](https://docs.unity3d.com/Manual/UnityRemote5.html)  
[Unity Remote 5 APK for Android Download](https://m.apkpure.com/unity-remote-5/com.unity3d.genericremote)

### **UI Toolkit- UDEMY Course**

[Modern Unity UI with UI Toolkit | Udemy](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/?couponCode=YOUTUBE_PROMO_MAR_23)

#### *Udemy: Debugging UI Document with Visual Studio Using BreakPoints*

[Debugging Using Breakpoints in Visual Studio](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33568170#overview)

#### *UI Toolkit \- GeometryChangedEvent (Udemy Lecture)*

(`GeometryChagnedEvent`)  
[https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594560\#overview](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594560#overview)

#### *UI Toolkit \- World Spade (Udemy Lecture)*

[https://www.youtube.com/watch?v=gXx\_j-6z8jY](https://www.youtube.com/watch?v=gXx_j-6z8jY)

#### *UI Toolkit \- Events Propagation (Udemy Lecture)*

[https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594570\#overview](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594570#overview)  
[https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594588\#overview](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594588#overview)  
(`Control all children with one event handler registered by the parent container`)  
[https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594608\#overview](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33594608#overview)

#### *Udemy: QueryBuilder*

[Using the UI Element QueryBuilder](https://www.udemy.com/course/modern-unity-ui-with-ui-toolkit/learn/lecture/33579682#overview)

#### *Udemy: Ui Toolkit Glass/Blur Effect*

[Various scripts related to Unity UI Toolkit (UIElements).](https://github.com/plyoung/UIElements#blurglass-effect)

#### *Udemy: Ui Toolkit Manipulators Example*

[https://github.com/R-Carver/UITK\_Resources\_Chapter09-13/tree/master/Assets/12\_Manipulators](https://github.com/R-Carver/UITK_Resources_Chapter09-13/tree/master/Assets/12_Manipulators)

### **UI Toolkit: References**

#### *UI Toolkit \- Setting the current element position to target element*

[https://forum.unity.com/threads/z-index-support.736781/](https://forum.unity.com/threads/z-index-support.736781/)

#### *UI Toolkit \- Official Roadmap Reference \[VERY IMP\]*

[UI Roadmap | Unity](https://unity.com/roadmap/unity-platform/ui)

#### *UI Toolkit \- Asset Store Sample Project \[Dragon Crashers\]*

[UI Toolkit Sample – Dragon Crashers | Tutorial Projects | Unity Asset Store](https://assetstore.unity.com/packages/essentials/tutorial-projects/ui-toolkit-sample-dragon-crashers-231178#description)

#### *UI Toolkit \- Expose custom control to UXML and UI Builder*

(`Create reusable UI components` )  
[Manual: Expose custom control to UXML and UI Builder](https://docs.unity3d.com/2022.2/Documentation/Manual/UIE-expose-custom-control-to-uxml.html#define-attributes-on-elements)

#### *UI Toolkit \- Encapsulate UXML documents with logic*

(`UxmlTraits` )  
[Encapsulate UXML documents with logic](https://docs.unity3d.com/2022.2/Documentation/Manual/UIE-encapsulate-uxml-with-logic.html)

#### *UI Toolkit \- How To Use Sprites*

[Official \- Feedback wanted : Sprite assets support \- Unity Forum](https://forum.unity.com/threads/feedback-wanted-sprite-assets-support.962958/)

#### *UI Toolkit \- Image Import Settings For Setting Background Images*

[Manual: Set background images](https://docs.unity3d.com/2022.2/Documentation/Manual/UIB-styling-ui-backgrounds.html)

#### *UI Toolkit \- BEM (Block Element Modifier): Usage of (\_ \_) & (- \-) is Styling*

[Manual: Best practices for USS](https://docs.unity3d.com/Manual/UIE-USS-WritingStyleSheets.html) 

#### *UI Toolkit \- YoYo (Loop) Transitions*

[Manual: Create looping transitions](https://docs.unity3d.com/2022.1/Documentation/Manual/UIE-transition-event-loop-example.html)

#### *UI Toolkit \- Create a transition event*

[Unity \- Manual: Create a transition event](https://docs.unity3d.com/2022.1/Documentation/Manual/UIE-transition-event-example.html)

#### *UI Toolkit \- url() & resources()*

[Unity \- Manual: url() and resource()](https://docs.unity3d.com/Manual/UIE-USS-PropertyTypes.html)

#### *UI Toolkit \- Load UXML and USS C\# scripts*

[Manual: Load UXML and USS C\# scripts](https://docs.unity3d.com/Manual/UIE-manage-asset-reference.html)

#### *UI Toolkit \- Reference files from UXML (src & path)*

[Manual: Reference other files from UXML](https://docs.unity3d.com/Manual/UIE-reference-other-files-from-uxml.html)

#### *UI Toolkit \- Reuse UXML Files*

[Reuse UXML files \- Manual](https://docs.unity3d.com/Manual/UIE-reuse-uxml-files.html)

#### *UI Toolkit \- Structure UI Example*

[Structure UI examples \- Manual](https://docs.unity3d.com/Manual/UIE-uxml-examples.html)

#### *UI Toolkit \- UXML Elements Reference*

[Manual: UXML elements reference](https://docs.unity3d.com/Manual/UIE-ElementRef.html)

#### *UI Toolkit \- Classes Reference*

[Scripting API: AbstractProgressBar](https://docs.unity3d.com/ScriptReference/UIElements.AbstractProgressBar.html)

#### *UI Toolkit \- Coordinate and position systems*

[Manual: Coordinate and position systems](https://docs.unity3d.com/Manual/UIE-coordinate-and-position-system.html)  
[Scripting API: VisualElementExtensions](https://docs.unity3d.com/ScriptReference/UIElements.VisualElementExtensions.html)

#### *Ui Toolkit \- Performance consideration for runtime UI*

To analyze the performance of the UI element at runtime (ex: usageHints):   
[Manual: Performance consideration for runtime UI](https://docs.unity3d.com/Manual/UIE-performance-consideration-runtime.html)

#### *Instantiate UI Elements at Runtime \- Unity 2022 UI Toolkit* 

[Making UI for Games with UI Toolkit \~ Unity 2022 Beginner's Guide to UI](https://www.youtube.com/watch?v=BG6NCgkbbiA&list=PLyH-qXFkNSxnKJxJB0ckzQ-ow_15qCv1l&ab_channel=Chris%27Tutorials) part-1  
[Instantiate UI Elements at Runtime - Unity 2022 UI Toolkit Tutorial](https://www.youtube.com/watch?v=GEHiGpD0NBs&ab_channel=Chris%27Tutorials) part-2

#### *UI Toolkit \- Radial Fill Element*

[UI Toolkit - Radial FIll Element](https://www.youtube.com/watch?v=yivtEeoHBC8&ab_channel=OkayRoman)

#### *How I Made UI For My Game*

[Unity UIToolkit tutorial & how I made UI for my game | UIElements](https://www.youtube.com/watch?v=-9XGF32Rkd0&ab_channel=Savallion)

#### *Unity UI Toolkit UQuery*

[Unity UI Toolkit - Finding Elements with UQuery - (1/6)](https://www.youtube.com/watch?v=OWs2_Z8KlSs&list=PLu_jCQwLZZq98_SsOM6JWgx3TWj5NRPzO)

#### *Unity UI Toolkit Custom Control \- Simple Popup Window*

[Unity UI Toolkit - Custom Control - simple PopupWindow - (1/6)](https://www.youtube.com/watch?v=c-K5KmQW-Zk&list=PLu_jCQwLZZq8lJXEKroIb7SKK3F8klGGo&ab_channel=MadCatTutorials)

#### *Unity UI Toolkit Flexbox*

[Unity UI Toolkit Flexbox  (1/11)  - Flex Basis](https://www.youtube.com/watch?v=lSyUs5Y0_SY&list=PLu_jCQwLZZq-yAubdFDfIkJ4wvX9QDufH&ab_channel=MadCatTutorials)

#### *Extending the Unity Editor with custom tools using UI Toolkit | Unite 2022*

[Extending the Unity Editor with custom tools using UI Toolkit | Unite 2022](https://www.youtube.com/watch?v=J2KNj3bw0Bw&ab_channel=Unity)

#### *Unity UI ToolKit in 5 mins*

[Unity UI Toolkit in 5 Minutes](https://www.youtube.com/watch?v=yUXFHAOXhcA&ab_channel=MadCatTutorials)

### 

#### *UI Toolkit Runtime \- Introduction to new Unity UI system*

[UI Toolkit for Runtime \[Unity\] - Teaser](https://www.youtube.com/watch?v=dJuzTlmCq44&list=PLmdJ8so4ffmvVKgECJF4FlnTfOq-2DcYa&index=1&ab_channel=CodewithMat%F0%9F%92%BE)

#### *Unity UI Toolkit Flexbox*

[Unity UI Toolkit Flexbox  (1/11)  - Flex Basis](https://www.youtube.com/watch?v=lSyUs5Y0_SY&list=PLu_jCQwLZZq-yAubdFDfIkJ4wvX9QDufH&ab_channel=MadCatTutorials)

#### *Unity UI Toolkit MeshGenerationContext*

[Class MeshGenerationContext | UI Toolkit | 1.0.0-preview.18](https://docs.unity3d.com/Packages/com.unity.ui@1.0/api/UnityEngine.UIElements.MeshGenerationContext.html)

### **CSS-TRICKS fex-box** 

[A Complete Guide to Flexbox | CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### **YogaLayout FlexBox** 

[Yoga Layout](https://yogalayout.com/)

### **Unity Mask/Drag**

[Unity MASKING - Ultimate Guide | Unity UI & Sprite Tutorial](https://www.youtube.com/watch?v=WlbMeORzwUU)

### **Unity Swipe Menu** 

[Swipe Control with Touch for Menu Level | Unity3D](https://www.youtube.com/watch?v=GURPmGoAOoM&ab_channel=AkbarProject)

### **Cut-Out Masking**

[Make a Cutout Mask in Unity\! (Inverted Mask)](https://www.youtube.com/watch?v=XJJl19N2KFM&ab_channel=CodeMonkey)

### **Ui Masking**

[Unity Ui Masking official lesson](https://learn.unity.com/tutorial/ui-masking#6032b763edbc2a0564a8968e)

### **Unity Engine Random.Range With Different Probabilities**

[Manual: Adding Random Gameplay Elements](https://docs.unity3d.com/2019.3/Documentation/Manual/RandomNumbers.html)

### **Unity Layer System**

[The Unity Layer System -  Game Dev Tutorial](https://www.youtube.com/watch?v=jqOODuCfMac&ab_channel=LostRelicGames)

### **Understanding Unity Engine Objects**

[Understanding Unity Engine Objects | Eyas's Blog](https://blog.eyas.sh/2020/10/unity-for-engineers-pt5-object-component/)

### **C\# Anonymous Types**

[C\# Anonymous Types](https://www.tutorialsteacher.com/csharp/csharp-anonymous-type)

### **C\# \- Abstract Classes**

[https://www.geeksforgeeks.org/c-sharp-abstract-classes/](https://www.geeksforgeeks.org/c-sharp-abstract-classes/)

### **PUN ERROR CODE LIST**

[Photon Unity Networking: ErrorCode Class Reference](https://doc-api.photonengine.com/en/pun/v1/class_error_code.html)

### **Faster Android Builds | Patching | Unity 2019.1 | Tutorial**

[Faster Android Builds | Patching | Unity 2019.1 | Tutorial](https://www.youtube.com/watch?v=DelJJB4vGQI&ab_channel=25games)

### **VIVOX Youtube tutorials**

[Voice & Text Chat in Unity](https://www.youtube.com/watch?v=XCqi0B1zqko&list=PLWpT9f90oEQetDA2fBwuxZxO4ZkySgMcM&ab_channel=InfallibleCode)

### **C\# Naming convention rules:**

[C\# Naming Conventions](https://www.c-sharpcorner.com/UploadFile/8a67c0/C-Sharp-coding-standards-and-naming-conventions/)

### **Unity Text Mesh Pro Rich Text Tags**

[Rich Text | TextMeshPro | 4.0.0-pre.2](https://docs.unity3d.com/Packages/com.unity.textmeshpro@4.0/manual/RichText.html)

### **EventTrigger**

[Scripting API: EventTrigger](https://docs.unity3d.com/2018.2/Documentation/ScriptReference/EventSystems.EventTrigger.html)  
[https://vasundhara.io/blogs/event-trigger-in-unity](https://docs.unity3d.com/2018.2/Documentation/ScriptReference/EventSystems.EventTrigger.html)

### **Firebase Messaging Youtube tutorial**

[Firebase Push Notifications in Unity 2020](https://www.youtube.com/watch?v=_8_dLm3R1gg&ab_channel=PixelbugStudio)  
[Unity Notification Package | Android Notifications 2021](https://www.youtube.com/watch?v=-6sRSOeuJK4&ab_channel=PixelbugStudio)

### **PLayFab friends system, photon Chat**

[Multiplayer In Unity Photon & Playfab \- YouTube](https://www.youtube.com/playlist?list=PLpt7xvHsgBxobW2yOYMLjtWc319bVN6II)

### **PUBLISHING GAME TO APP STORE**

[Publishing a Unity Game to App Store in 2021](https://www.youtube.com/watch?v=z4vX4JdIxv4&ab_channel=MrMProgramming)  
[Publishing a Unity Game to Google Play Market in 2021](https://www.youtube.com/watch?v=vVAbx7KuWng&ab_channel=MrMProgramming)  
[Building to iOS - Unity 2021 \[Provisioning profile, App store, Apple Developer\]](https://www.youtube.com/watch?v=9xQw0p0w9Ac&ab_channel=Epitome)

### **OneSignal Example** 

[OneSignal-Unity-SDK/OneSignalExampleBehaviour.cs at main](https://github.com/OneSignal/OneSignal-Unity-SDK/blob/main/OneSignalExample/Assets/OneSignal/Example/OneSignalExampleBehaviour.cs)  
[OneSignal SDK Reference](https://github.com/OneSignal/OneSignal-Unity-SDK/blob/main/OneSignalExample/Assets/OneSignal/Example/OneSignalExampleBehaviour.cs)  
[https://documentation.onesignal.com/docs/sdk-reference](https://github.com/OneSignal/OneSignal-Unity-SDK/blob/main/OneSignalExample/Assets/OneSignal/Example/OneSignalExampleBehaviour.cs)

### **Firebase & OneSignal YouTube**

[How do I send push notifications to OneSignal?](https://www.youtube.com/watch?v=R7am6vTagjU&ab_channel=SNDevelops)

### **Update vs. FixedUpdate vs. LateUpdate in Unity**

[Update vs. FixedUpdate vs. LateUpdate in Unity \- LogRocket Blog](https://blog.logrocket.com/update-vs-fixedupdate-vs-lateupdate-in-unity/)

### **Asynchronous Programming / Programming concepts.**

[Asynchronous programming \- C\# | Microsoft Learn](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)

### **Params**

[C\# Params \- javatpoint](https://www.javatpoint.com/c-sharp-params#:~:text=In%20C%23%2C%20params%20is%20a,keyword%20in%20a%20function%20declaration.)

### **HttpClient Usage with Await Task**

[The Task Asynchronous Programming (TAP) model with async and await" | Microsoft Learn](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/task-asynchronous-programming-model)

### **Best json formatter**

[JSON Formatter](https://jsonformatter.org/)

### **Newtonsoft.Json**

[NuGet Gallery | Newtonsoft.Json 13.0.3](https://www.nuget.org/packages/Newtonsoft.Json/)

### **Photon RpcTarget. AllBuffered, OthersBuffered etc.**

[Photon Unity Networking 2: Public API](https://doc-api.photonengine.com/en/pun/v2/group__public_api.html)

### **Events**

[Events in C\#](https://www.tutorialsteacher.com/csharp/csharp-event)

### **Strings**

[C\# String Compare() method \- javatpoint](https://www.javatpoint.com/csharp-string-compare)

### **CharEnumerator**

[CharEnumerator Class (System) | Microsoft Learn](https://learn.microsoft.com/en-us/dotnet/api/system.charenumerator?view=net-7.0)

### **One Key to multiple values dictionary in C\#?**

[One Key to multiple values dictionary in C\#? \- Stack Overflow](https://stackoverflow.com/questions/14987156/one-key-to-multiple-values-dictionary-in-c)  
[C\# | Func delegate \- GeeksforGeeks](https://www.geeksforgeeks.org/c-sharp-func-delegate/#:~:text=Func%20is%20generally%20used%20for,type%20or%20of%20different%20types.)

### **Use of hasSets instead of list/array. HashSet eliminates duplicates.**

[Sets in C](https://www.tutorialspoint.com/sets-in-chash)

### **Is a stack better than a list?**

Use the correct tool for the job; use a List when you need "random" access to any element in the collection. Use a Stack when you want to enforce the more limited "top-only" access to elements in the array. Use a Queue when you want to enforce a FIFO "pipeline"; items go in one end, out the other.

### **Structs**

[Struct in C\#](https://www.tutorialsteacher.com/csharp/csharp-struct)

### **Fields vs Properties**

(Using Properties, you can raise an event, when the value of the property is changed (aka. PropertyChangedEvent) or before the value is changed to support cancellation.)  
https://stackoverflow.com/questions/295104/what-is-the-difference-between-a-field-and-a-property

It's a best practice not to use public variables since you can accidentally make algorithmic mistakes and large interconnections of classes in projects. Sometimes you'll only what data to be read-only outside of the scope of the class in which you use a property that only has a GET accessor. This way the compiler can point out unintentional assignments.

### **Public Variable vs Property variables**

[Public variable vs Property variables](https://social.msdn.microsoft.com/Forums/en-US/70b1882f-3076-4e47-9914-db4656fe2eb4/public-variable-vs-property-variables?forum=netfxbcl)

[image1]: <data:image/png;base64,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>