# Mi-primer-proyecto-Android
Mi primer proyecto Android
<resources>
    <dimen name="text_size_large">24sp</dimen>
    <dimen name="text_size_small">18sp</dimen>
</resources>
<resources>
    <dimen name="text_size_large">32sp</dimen>
    <dimen name="text_size_small">24sp</dimen>
</resources>
android:textSize="@dimen/text_size_large"
override fun onConfigurationChanged(newConfig: Configuration) {
    super.onConfigurationChanged(newConfig)
    // Handle orientation changes if needed
}
<activity
    android:name=".MainActivity"
    android:configChanges="orientation|screenSize|keyboardHidden"
    android:label="@string/app_name">
    <intent-filter>
        <action android:name="android.intent.action.MAIN" />
        <category android:name="android.intent.category.LAUNCHER" />
    </intent-filter>
</activity>
