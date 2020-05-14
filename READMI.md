<table>
<thead>
<tr>
<th>Description</th>
<th>Command Swift &lt; 3 OR Objc</th>
<th>Swift 3</th>
</tr>
</thead>
<tbody>
<tr>
<td>Settings Section <strong>topmost level</strong></td>
<td>From Widget (<code>Prefs:</code>)</td>
<td>From App (<code>App-prefs:</code>)</td>
</tr>
<tr>
<td>About</td>
<td><code>prefs:root=General&amp;path=About</code></td>
<td><code>App-prefs:root=General&amp;path=About</code></td>
</tr>
<tr>
<td>Accessibility</td>
<td><code>prefs:root=General&amp;path=ACCESSIBILITY</code></td>
<td><code>App-prefs:root=General&amp;path=ACCESSIBILITY</code></td>
</tr>
<tr>
<td>Account Settings</td>
<td><code>prefs:root=ACCOUNT_SETTINGS</code></td>
<td><code>App-prefs:root=ACCOUNT_SETTINGS</code></td>
</tr>
<tr>
<td>Airplane Mode</td>
<td><code>prefs:root=AIRPLANE_MODE</code></td>
<td><code>App-prefs:root=AIRPLANE_MODE</code></td>
</tr>
<tr>
<td>Autolock iOS &lt; 10</td>
<td><code>prefs:root=General&amp;path=AUTOLOCK</code></td>
<td><code>App-prefs:root=General&amp;path=AUTOLOCK</code></td>
</tr>
<tr>
<td>Auto-Lock iOS &gt; 10</td>
<td><code>prefs:root=DISPLAY&amp;path=AUTOLOCK</code></td>
<td><code>App-prefs:root=DISPLAY&amp;path=AUTOLOCK</code></td>
</tr>
<tr>
<td>Apple Pay / Wallet</td>
<td><code>shoebox://url-scheme</code></td>
<td><code>shoebox://url-scheme</code></td>
</tr>
<tr>
<td>Battery</td>
<td><code>prefs:root=BATTERY_USAGE</code></td>
<td><code>App-prefs:root=BATTERY_USAGE</code></td>
</tr>
<tr>
<td>Brightness</td>
<td><code>prefs:root=Brightness</code></td>
<td><code>App-prefs:root=Brightness</code></td>
</tr>
<tr>
<td>Bluetooth iOS &lt; 9</td>
<td><code>prefs:root=General&amp;path=Bluetooth</code></td>
<td><code>App-prefs:root=General&amp;path=Bluetooth</code></td>
</tr>
<tr>
<td>Bluetooth iOS &gt; 9</td>
<td><code>prefs:root=Bluetooth</code></td>
<td><code>App-prefs:root=Bluetooth</code></td>
</tr>
<tr>
<td>Castle</td>
<td><code>prefs:root=CASTLE</code></td>
<td><code>App-prefs:root=CASTLE</code></td>
</tr>
<tr>
<td>Cellular Usage</td>
<td><code>prefs:root=General&amp;path=USAGE/CELLULAR_USAGE</code></td>
<td><code>App-prefs:root=General&amp;path=USAGE/CELLULAR_USAGE</code></td>
</tr>
<tr>
<td>Configuration List</td>
<td><code>prefs:root=General&amp;path=ManagedConfigurationList</code></td>
<td><code>App-prefs:root=General&amp;path=ManagedConfigurationList</code></td>
</tr>
<tr>
<td>Date and Time</td>
<td><code>prefs:root=General&amp;path=DATE_AND_TIME</code></td>
<td><code>App-prefs:root=General&amp;path=DATE_AND_TIME</code></td>
</tr>
<tr>
<td>Do not disturb</td>
<td><code>prefs:root=General&amp;path=DO_NOT_DISTURB</code></td>
<td><code>App-prefs:root=General&amp;path=DO_NOT_DISTURB</code></td>
</tr>
<tr>
<td>Facetime</td>
<td><code>prefs:root=FACETIME</code></td>
<td><code>App-prefs:root=FACETIME</code></td>
</tr>
<tr>
<td>General</td>
<td><code>prefs:root=General</code></td>
<td><code>App-prefs:root=General</code></td>
</tr>
<tr>
<td>Internet Tethering</td>
<td><code>prefs:root=INTERNET_TETHERING</code></td>
<td><code>App-prefs:root=INTERNET_TETHERING</code></td>
</tr>
<tr>
<td>iTunes</td>
<td><code>prefs:root=MUSIC</code></td>
<td><code>App-prefs:root=MUSIC</code></td>
</tr>
<tr>
<td>iTunes Equalizer</td>
<td><code>prefs:root=MUSIC&amp;path=EQ</code></td>
<td><code>App-prefs:root=MUSIC&amp;path=EQ</code></td>
</tr>
<tr>
<td>iTunes Volume</td>
<td><code>prefs:root=MUSIC&amp;path=VolumeLimit</code></td>
<td><code>App-prefs:root=MUSIC&amp;path=VolumeLimit</code></td>
</tr>
<tr>
<td>Keyboard</td>
<td><code>prefs:root=General&amp;path=Keyboard</code></td>
<td><code>App-prefs:root=General&amp;path=Keyboard</code></td>
</tr>
<tr>
<td>Deeper in Keyboard</td>
<td><code>prefs:root=General&amp;path=Keyboard/KEYBOARDS</code></td>
<td><code>App-prefs:root=General&amp;path=Keyboard/KEYBOARDS</code></td>
</tr>
<tr>
<td>Lang International</td>
<td><code>prefs:root=General&amp;path=INTERNATIONAL</code></td>
<td><code>App-prefs:root=General&amp;path=INTERNATIONAL</code></td>
</tr>
<tr>
<td>Location Services</td>
<td><code>prefs:root=Privacy&amp;path=LOCATION</code></td>
<td><code>App-Prefs:root=Privacy&amp;path=LOCATION</code></td>
</tr>
<tr>
<td>Mobile Data</td>
<td></td>
<td><code>prefs:root=MOBILE_DATA_SETTINGS_ID</code></td>
</tr>
<tr>
<td>Network</td>
<td><code>prefs:root=General&amp;path=Network</code></td>
<td><code>App-prefs:root=General&amp;path=Network</code></td>
</tr>
<tr>
<td>Nike iPod</td>
<td><code>prefs:root=NIKE_PLUS_IPOD</code></td>
<td><code>App-prefs:root=NIKE_PLUS_IPOD</code></td>
</tr>
<tr>
<td>Notes</td>
<td><code>prefs:root=NOTES</code></td>
<td><code>App-prefs:root=NOTES</code></td>
</tr>
<tr>
<td>Notifications ID</td>
<td><code>prefs:root=NOTIFICATIONS_ID</code></td>
<td><code>App-prefs:root=NOTIFICATIONS_ID</code></td>
</tr>
<tr>
<td>Passcode / Touch ID</td>
<td><code>prefs:root=TOUCHID_PASSCODE</code></td>
<td><code>App-prefs:root=TOUCHID_PASSCODE</code></td>
</tr>
<tr>
<td>Passbook</td>
<td><code>prefs:root=PASSBOOK</code></td>
<td><code>App-prefs:root=PASSBOOK</code></td>
</tr>
<tr>
<td>Phone</td>
<td><code>prefs:root=Phone</code></td>
<td><code>App-prefs:root=Phone</code></td>
</tr>
<tr>
<td>Photo Camera Roll</td>
<td><code>prefs:root=Photos</code></td>
<td><code>App-prefs:root=Photos</code></td>
</tr>
<tr>
<td>Privacy</td>
<td><code>Prefs:root=Privacy</code></td>
<td><code>App-prefs:root=Privacy</code></td>
</tr>
<tr>
<td>Profiles &amp; Device Management</td>
<td><code>Prefs:root=General&amp;path=ManagedConfigurationList</code></td>
<td><code>App-prefs:root=General&amp;path=ManagedConfigurationList</code></td>
</tr>
<tr>
<td>Reset</td>
<td><code>prefs:root=General&amp;path=Reset</code></td>
<td><code>App-prefs:root=General&amp;path=Reset</code></td>
</tr>
<tr>
<td>Ringtone</td>
<td><code>prefs:root=Sounds&amp;path=Ringtone</code></td>
<td><code>App-prefs:root=Sounds&amp;path=Ringtone</code></td>
</tr>
<tr>
<td>Siri</td>
<td><code>prefs:root=SIRI</code></td>
<td><code>App-prefs:root=SIRI</code></td>
</tr>
<tr>
<td>Safari</td>
<td><code>prefs:root=Safari</code></td>
<td><code>App-prefs:root=Safari</code></td>
</tr>
<tr>
<td>Siri iOS &lt; 10?</td>
<td><code>prefs:root=General&amp;path=Assistant</code></td>
<td><code>App-prefs:root=General&amp;path=Assistant</code></td>
</tr>
<tr>
<td>Siri iOS &gt; 10?</td>
<td><code>prefs:root=SIRI</code></td>
<td><code>App-prefs:root=SIRI</code></td>
</tr>
<tr>
<td>Sounds</td>
<td><code>prefs:root=Sounds</code></td>
<td><code>App-prefs:root=Sounds</code></td>
</tr>
<tr>
<td>Software Update</td>
<td><code>prefs:root=General&amp;path=SOFTWARE_UPDATE_LINK</code></td>
<td><code>App-prefs:root=General&amp;path=SOFTWARE_UPDATE_LINK</code></td>
</tr>
<tr>
<td>Storage &amp; Backup</td>
<td><code>prefs:root=CASTLE&amp;path=STORAGE_AND_BACKUP</code></td>
<td><code>App-prefs:root=CASTLE&amp;path=STORAGE_AND_BACKUP</code></td>
</tr>
<tr>
<td>Store</td>
<td><code>prefs:root=STORE</code></td>
<td><code>App-pref:root=STORE</code></td>
</tr>
<tr>
<td>Twitter</td>
<td><code>prefs:root=TWITTER</code></td>
<td><code>App-prefs:root=TWITTER</code></td>
</tr>
<tr>
<td>Usage</td>
<td><code>prefs:root=General&amp;path=USAGE</code></td>
<td><code>App-prefs:root=General&amp;path=USAGE</code></td>
</tr>
<tr>
<td>Video</td>
<td><code>prefs:root=VIDEO</code></td>
<td><code>App-prefs:root=VIDEO</code></td>
</tr>
<tr>
<td>VPN</td>
<td><code>prefs:root=General&amp;path=Network/VPN</code></td>
<td><code>App-prefs:root=General&amp;path=Network/VPN</code></td>
</tr>
<tr>
<td>Wallpaper</td>
<td><code>prefs:root=Wallpaper</code></td>
<td><code>App-prefs:root=Wallpaper</code></td>
</tr>
<tr>
<td>WIFI</td>
<td><code>prefs:root=WIFI</code></td>
<td><code>App-prefs:root=WIFI</code></td>
</tr>
</tbody>
</table>
