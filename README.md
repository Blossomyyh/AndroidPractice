# AndroidPractice
several projects learned from codelab
1. Android Architecture Components -- android Jetpack

   - **manifests**: Contains the `AndroidManifest.xml` file.
   - **java**: Contains the Java source code files, including JUnit test code.
   - **res**: Contains all non-code resources, such as XML layouts, UI strings, and bitmap images.

2. A jetpack App

   ViewModel is a class that is responsible for preparing and managing the data for an `Activity` or a `Fragment`.

   - LiveData
     - 当Activity停止时不会引起崩溃
     - 这是因为组件处于非激活状态时，不会收到LiveData中数据变化的通知
     - LiveData能够感知组件的生命周期，所以就完全不需要在代码中告诉LiveData组件的生命周期状态
     - 
