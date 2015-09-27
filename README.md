hangouts_json_to_csv
===============

<p>
A Python script that converts Google Hangouts conversations stored in JSON format to CSV format.
</p>

<p>
Google Takeout (https://www.google.com/settings/takeout) allows you to download all your Google account related data (mails, calendar data, contacts, Google+ posts, Hangouts conversations...)
It creates a .zip archive containing a file which contains the Hangouts conversations encoded in JSON format.
This script allows you to convert that file to simpler CSV file containing timestamp, sender and text of message. It creates seperate CSV file per conversation.
</p>

<p>
Run:
<code> python <script_name> <file_json> <out_dir> </code>
<ul>
	<li> <file_json> file that you want to convert </li>
	<li><out_dir> directory in which all generated CSV files will be stored.</li>
</ul>
</p>


