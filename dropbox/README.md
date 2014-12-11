<code>push_to_dropbox</code>

The script is used to push the files changed in the latest commit to your dropbox account, all you have to do is the following:

* in <code>.git/hooks</code> add file named <code>post-commit</code> with only one line <code>push_to_dropbox</code>
* add a file named <code>dropbox_keys.ini</code> having the following form containing your <code>app_secret</code> and <code>app_key</code>, it will use the flow to get your <code>access_token</code> that will be stored in the <code>.access_token</code> file

The <code>dropbox_keys.ini</code> should be like this

<code>
[Keys]

app_key: lt9tfpg4pkbckaa

app_secret: pgbqsx8bqkoqq5ux
</code>
