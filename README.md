# Facebook AccountKit using Android

Ini adalah sample project Android yang menggunakan AccountKit untuk verifikasi user.

## Dependecy

Tambahkan ke build.gradle

<pre><code>compile 'com.facebook.android:facebook-android-sdk:4.+'
compile 'com.facebook.android:account-kit-sdk:4.+'</pre></code>

## Permission

Tambahkan ke AndroidManifest

<pre><code>
&lt;uses-permission android:name="android.permission.INTERNET"/&gt;
</pre></code>

## FB App

Buat Facebook App menggunakan account FB Developer. Tambahkan AccountKit dari menu Product. Catat App IDD dan AccountKit Client Token. Pastikan untuk mendisable Client Access Token Flow.

Selengkapnya bisa dilihat [di sini](https://developers.facebook.com/docs/accountkit/android)

## SETUP

### strings.xml

Masukkan App Id dan AccountKit Client Token ke values/strings.xml

<pre><code>
&lt;string name="FACEBOOK_APP_ID"&gt;[YOUR APP ID]&lt;/string&gt;
&lt;string name="ACCOUNT_KIT_CLIENT_TOKEN"&gt;[YOUR ACCOUNT KIT CLIENT TOKEN]&lt;/string&gt;
</pre></code>