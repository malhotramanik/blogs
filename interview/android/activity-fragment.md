1. Explain Activity Life Cycle and Most Importantly What will be the Life cycle (In Order) If Activity B is Launched from Activity A.
https://stackoverflow.com/a/43346281/13733003

2. Explain Fragment Life Cycle, How the Activity Life cycle and Fragment Life Cycle gets called In Order, RetainInstanceState in Fragment
(https://medium.com/androiddevelopers/the-android-lifecycle-cheat-sheet-part-iii-fragments-afc87d4f37fd)


3. Fragment Add vs Fragment Replace, Explain with using Backstack and Without using backstack
https://stackoverflow.com/questions/18634207/difference-between-add-replace-and-addtobackstack

4. Activity Life cycle when Dialog is opened — (hint:- Don’t get confused b/w system-generated Dialog and your own app dialog)
https://android.jlelse.eu/in-depth-analysis-of-activitys-lifecycle-676179d8a520

5. Why to use setContentView() in onCreate() callback method?
https://androidride.com/what-setcontentview-android-studio/

6. #### Why it is recommended to use Default Constructor to create a Fragment
>It is used in the case when device has to restore the state of a fragment. No data will be passed and a default fragment will be created and then the state will be restored. Since the system has no way to know what you passed in your constructor or your newInstance, default constructor will be used and saved bundle should be passed via onCreate after the fragment is actually instantiated with the default constructor.
