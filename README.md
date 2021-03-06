## Main repository for the FLAG Android Training - 2015

### Bibliography

- Book: [Learning Android - Marko Gargenta](http://shop.oreilly.com/product/0636920010883.do)

- Official Documentation for Android: [Android Developers](http://developer.android.com/index.html)

### Summaries

- **10-04-2015**:

	- Training presentation.
	
	- Install and configure the VCS Git and the connection with the Github's remote repository.	
	
	- Learn the Git's basics commands
		
		- git add
		- git commit
		- git push
		- git pull
		
	
	*Links/resources from this day*:
	
	- [Git](http://git-scm.com/)
	
	- [Pro Git](http://git-scm.com/book/en/v2) - Official Git book (free).
	
	- [SourceTree](http://www.sourcetreeapp.com/) - Because not everyone likes the Command Line :-P
	
	*TPC*:
	
	- See what is the .gitignore file.
	
	- Push the first Android Application to the remote repository.

---

- **13-04-2015**:

	- Discuss about the .gitignore file.
	
	- Discuss the Android Stack and the JVM vs Dalvik vs ART virtual machines.
	
	- IoC - Inversion of Control.
	
	- First Android project:
	
		- The Android's project folder structure
		
		- Activity layout (usage of the LinearLayout)
		
		- Android's R class (Resources class)
		
		- Activity class (ActionListeners, get the references for the Views components)
		
	*Links/resources from this day*:
	
	- [IoC](http://en.wikipedia.org/wiki/Inversion_of_control)
	
	- [Android Studio](https://developer.android.com/tools/studio/index.html)
	
	- [Activity](https://developer.android.com/reference/android/app/Activity.html)
	
	- [R Class](https://developer.android.com/reference/android/R.html)
	
	- [LinearLayout](https://developer.android.com/guide/topics/ui/layout/linear.html)
		
	*TPC*:
	
	- Search for the reason why the Activity loses is state when the device is rotated.

---

- **15-04-2015**:

	- Discuss the Activity Life cylce.
	
	- Use the onSaveInstanceState and onRestoreInstaceSate to save state when the activity is rotated.
	
	*Links/resources from this day*:
	
	- [Activity](http://developer.android.com/reference/android/app/Activity.html) 
	
---

- **17-04-2015**:

	- Use the Toasts.
	
	- Create one button programmatically.
	
	- Navigation between Activities.
	
	- Intents (implicit and explicit).
	
	- Use the intents to pass information between Activities.
	
	- Context (Activity context vs Application context). See the possible memory leaks when the context is not used correctly.
	
	
	*Links/resources from this day*:
	
	- [Toast](http://developer.android.com/reference/android/widget/Toast.html)
		
	- [startActivity](http://developer.android.com/reference/android/content/Context.html#startActivity%28android.content.Intent%29)
		
	- [Intent](http://developer.android.com/reference/android/content/Intent.html)
		
	- [Context](http://developer.android.com/reference/android/content/Context.html)
		
	- [Avoiding memory leaks](http://android-developers.blogspot.pt/2009/01/avoiding-memory-leaks.html)
	
	*TPC*:
	
	- Update the counter value through the startActivityForResult method.
	
---

- **20-04-2015**:

	- StartActivityForResult method.
	
	- Resources files, namely the string.xml and the languages support.
	
	- Threads. UI Thread and the creation of one alternative Thread (Java style).
	
	- Talk about the HTTP protocol and the Android's HttpURLConnection.
	
	- Start the discussion about the AsyncTask abstract class.
	
	
	*Links/resources from this day*:
	
	- [startActivityForResult](http://developer.android.com/reference/android/app/Activity.html#startActivityForResult%28android.content.Intent,%20int%29) 
	
	- [Localizing with Resources](http://developer.android.com/guide/topics/resources/localization.html)
	
	- [Java Threads](http://docs.oracle.com/javase/tutorial/essential/concurrency/runthread.html)
	
	- [HTTP RFC2616](http://tools.ietf.org/html/rfc2616), for more information purpose only.
	
	- [HttpURLConnection](http://developer.android.com/reference/java/net/HttpURLConnection.html)
	
	- [HttpURLConnection vs Apache UrlConnection](http://android-developers.blogspot.in/2011/09/androids-http-clients.html)
	
	- [AsyncTask](http://developer.android.com/reference/android/os/AsyncTask.html)
	
	*TPC*:
	
	- Replace the code marked as "Bad Code" in the MainActivity class from the AsyncTaskDemo project, with one AsyncTask.

---

- **22-04-2015**:

	- AsyncTask.
	
	- Services (Started Services and Bound Services).
	
	
	*Links/resources from this day*:
	
	- [AsyncTask](http://developer.android.com/reference/android/os/AsyncTask.html)
	- [Services](http://developer.android.com/guide/components/services.html)

	*TPC*:
	
	- Replace the started service from the project TemperatureApp with one [IntentService](http://developer.android.com/reference/android/app/IntentService.html)
	
---

- **24-04-2015**:

	- AlarmManager for scheduling repeating tasks.
	
	- NotificationManager for notify the user in the notification bar.
	

	*Links/resources from this day*:
	
	- [AlarmManager](http://developer.android.com/reference/android/app/AlarmManager.html)
	
	- [NotificationManager](http://developer.android.com/reference/android/app/NotificationManager.html)
	
	- [Scheduling Repeating Alarms](http://developer.android.com/training/scheduling/alarms.html)

---

- **27-04-2015**:

	- BroadcastReceivers.
	
	- SharedPreferences.
	
	- Options menu.
	
	- Class Application.
	

	*Links/resources from this day*:
	
	- [BroadcastReceivers](http://developer.android.com/reference/android/content/BroadcastReceiver.html)
	
	- [SharedPreferences](http://developer.android.com/guide/topics/data/data-storage.html#pref)
	
	- [Options menu](http://developer.android.com/reference/android/view/Menu.html)
	
	- [Class Application](http://developer.android.com/reference/android/app/Application.html)
	

### [Android Project](https://github.com/challengeit/Flag_Android_2015/wiki/Projecto-Android) 


