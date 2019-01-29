# Android Learning Topics

ViewGroups | Suggested Seniority
----|----
RelativeLayout, LinearLayout, ScrollView | Engineer 1
Basic properties | Engineer 1
ConstraintLayout, CoordinatorLayout, SwipeRefreshLayout | Engineer 2
RelativeLayout vs ConstraintLayout | Engineer 2
Responsive UI | Engineer 2

Views | Suggested Seniority
----|----
Types: ImageView, Button, TextView, EditText, TextInputEditText. | Engineer 1
Basic properties | Engineer 1
Programmatic ClickListeners vs xml | Engineer 1
States: visible, invisible, etc. | Engineer 1

Activities | Suggested Seniority
----|----
Definition | Engineer 1
Lifecycle | Engineer 1
Implementation (xml / programmatically) | Engineer 1
FragmentManager | Engineer 1
Lifecycle (callbacks and what happens in every call) | Engineer 2
Activity states (background, foreground, etc.) | Engineer 2

Fragments | Suggested Seniority
----|----
Definition | Engineer 1
Lifecycle | Engineer 1
Implementation (xml / programmatically) | Engineer 1
FragmentManager | Engineer 1
Lifecycle (callbacks and what happens in every call) | Engineer 2
Relation with Activity lifecycle | Engineer 2
Communication between fragments and activities (Callbacks) | Engineer 2
Communication between fragments (Callbacks) | Engineer 2
Communication between fragments using ViewModel | Engineer 3

Broadcast Receivers | Suggested Seniority
----|----
Definition | Engineer 1
Lifecycle | Engineer 1
Implementation (xml / programmatically) | Engineer 1
Manifest definition vs programmatically - Intent actions definition. | Engineer 2
LocalBroadcastManager, why and when to use it? (Keep events inside app context) | Engineer 2

Services | Suggested Seniority
----|----
Definition | Engineer 1
Common uses | Engineer 1
Types (Services vs BoundServices) | Engineer 2
Implementation (Extending Service class or IntentService class) | Engineer 2
Differences between Service and IntentService. | Engineer 2
How to start a service? How to stop a service? | Engineer 2
BoundServices implementation | Engineer 3

Content providers | Suggested Seniority
----|----
Definition | Engineer 1
Types: General vs Custom. | Engineer 2
How to use general content providers?| Engineer 2
Custom content providers implementation | Senior
Concurrency manager (CRUD operations with synchronized) | Senior

Manifest | Suggested Seniority
----|----
Tags. Android components (Activities, BReceivers, Services, CProviders) | Engineer 1
Permissions (definition). App configuration (icons, name, theme, etc.) | Engineer 1
Intent filters, Intent actions, Data types, etc. | Engineer 2

Gradle | Suggested Seniority
----|----
What is it for? | Engineer 1
Build.gradle (project and app module, build and compilation tasks) | Engineer 1
settings.gradle | Engineer 2
gradle.properties | Engineer 2
BuildVariants: main, release, prod, debug, etc. | Engineer 3
Custom tasks, flavors, dimensions | Engineer 3

IDE handling | Suggested Seniority
----|----
Android Studio - InteliJ | Engineer 1
Log analysis | Engineer 1
AVD | Engineer 1
Breakpoints and debugger | Engineer 2
Emulators: AS emulator vs Genymotion | Engineer 2
SDK Manager | Engineer 2
Layout inspector | Engineer 2

Adapters | Suggested Seniority
----|----
BaseAdapter and implementations (SimpleCursorAdapter, ArrayAdapter, etc.) | Engineer 1
RecyclerView.Adapter | Engineer 2

Intent | Suggested Seniority
----|----
Definition. Properties: putExtra, etc. | Engineer 1
Implicit vs explicit Intents | Engineer 1
Intent services, Intent filters | Engineer 2
PendingIntent | Engineer 2

Modal Views | Suggested Seniority
----|----
Alerts | Engineer 1
Dialogs | Engineer 1
Progressbar | Engineer 1

Resources (Basic knowledge) | Suggested Seniority
----|----
Adding and using strings, dimensions, colors, etc. | Engineer 1

Permissions | Suggested Seniority
----|----
Manifest permissions vs Runtime permissions. | Engineer 2
Runtime permissions implementation. | Engineer 2
Libraries for runtime permissions (e.g. Dexter) | Engineer 3

Material design | Suggested Seniority
----|----
General knowledge of Material design components. | Engineer 2
Implementation. | Engineer 2
Libraries (legacy: support - androidx) | Engineer 2
Animations, transitions, transformations | Engineer 3
Material design guidelines - brandlines | Engineer 3

Conectivity | Suggested Seniority
----|----
Retrofit / Retrofit2 (Basic knowledge) | Engineer 2
Serialization and deserialization (native way) | Engineer 2
Serialization and deserialization using libraries (Gson, Jackson, etc.) | Engineer 2
Retrofit internal behaviour | Engineer 3
HttpUrlConnection | Engineer 3

Tests | Suggested Seniority
----|----
Unit Test (Basic knowledge) | Engineer 2
Instrumented Test (Basic knowledge) | Engineer 2
Unit Test, libraries | Engineer 3
Instrumented Test | Engineer 3
UI test automation (Expresso, Appium) | Senior

Threads | Suggested Seniority
----|----
Android threads | Engineer 2
Thread UI | Engineer 2

AsyncTask | Suggested Seniority
----|----
Definition | Engineer 2
Implementation | Engineer 2
Memory Leaks (explanation and how to solve it) | Engineer 3

ViewPager | Suggested Seniority
----|----
Definition | Engineer 2
Implementation | Engineer 2
PagerAdapter | Engineer 2
PagerTransformer for animations | Engineer 3

Storage | Suggested Seniority
----|----
Location (storage structure) | Engineer 2
SharedPreferences (global context or activity) | Engineer 2
SQLite - Implementation | Engineer 2
Internal vs External (device memory vs SD external storage) | Engineer 2

Notifications | Suggested Seniority
----|----
Definition | Engineer 2
Implementation | Engineer 2
Notification builder | Engineer 2
Notification Manager | Engineer 2
Local notifications vs Push notifications (Google cloud messaging, Firebase) | Senior

App configuration | Suggested Seniority
----|----
Screen rotation | Engineer 2
Screen densities | Engineer 2
Internationalization | Engineer 2
ConfigurationManager | Engineer 3

Xml tags in layouts | Suggested Seniority
----|----
Include | Engineer 2
Merge | Engineer 2
Fragment | Engineer 2

Android architecture (ART) | Suggested Seniority
----|----
Architecture layers | Engineer 2

Widgets | Suggested Seniority
----|----
Statics and dynamics | Engineer 2

CustomViews | Suggested Seniority
----|----
Gradients and shadows handling, etc. | Engineer 3

ViewModel | Suggested Seniority
----|----
Definition. What is it for? | Engineer 3
Application cases | Engineer 3
Implementation | Engineer 3
ViewModel lifecycle | Engineer 3

Third party libraries for storage | Suggested Seniority
----|----
Realm, Firebase, etc. | Engineer 3
Advantages over native option | Engineer 3

Architecture patterns | Suggested Seniority
----|----
MVP | Engineer 3
MVC | Engineer 3
MVVM | Engineer 3

Performance and security | Suggested Seniority
----|----
Basic concepts | Engineer 3
Code obfuscation | Senior
Proguard - Dexguard | Senior
Lint | Senior

Media handling | Suggested Seniority
----|----
Video, audio and images | Engineer 3

Kotlin | Suggested Seniority
----|----
Differences with Java | Engineer 3
Why should we use Kotlin? Advantages | Engineer 3
Syntax and semantics | Engineer 3

Third party libraries | Suggested Seniority
----|----
Glide | Engineer 3
Picasso | Engineer 3
Volley | Engineer 3
Others | Engineer 3

Play Store app publication | Suggested Seniority
----|----
Signed APK generation | Engineer 3
Version control inside Google Play Console | Engineer 3

Firebase | Suggested Seniority
----|----
Definition. What is it for? Android app integration | Senior
Uses (database, push notifications, etc.) | Senior

Task | Suggested Seniority
----|----
Definition | Senior
Features | Senior
TaskStackBuilder | Senior
TaskAffinity | Senior
Task FLAGS | Senior

DeepLink | Suggested Seniority
----|----
Implementation and AS Wizard | Senior

JobScheduler | Suggested Seniority
----|----
Definition - Use | Senior
Implementation | Senior

Sensors | Suggested Seniority
----|----
Accelerometer, gyroscope, magnetic field, light, etc. | Senior

Bluetooth | Suggested Seniority
----|----
Intent handling, permissions, custom service | Senior

Canvas | Suggested Seniority
----|----
Drawing using View and SurfaceView | Senior

Resources optimization | Suggested Seniority
----|----
Memory, Battery | Senior

Jetpack | Suggested Seniority
----|----
Definition | Senior
Components | Senior

Accessibility | Suggested Seniority
----|----
Basic concepts | Senior
Implementation | Senior

AlarmManager | Suggested Seniority
----|----
Definition | Senior
Implementation | Senior

Google maps API's | Suggested Seniority
----|----
Google maps integration | Senior
Apis: geocoding, distance, etc. | Senior
Google developer's console (Create api key, api key restrictions) | Senior

Reactive programming | Suggested Seniority
----|----
Basic concepts | Senior
RxJava | Senior
