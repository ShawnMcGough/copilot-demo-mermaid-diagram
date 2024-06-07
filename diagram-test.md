```mermaid
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
branch master
commit "May 1st"
branch add_login
checkout add_login
commit "May 8th"
checkout master
merge add_login
commit "May 15th"
branch create_login_button
checkout create_login_button
commit "May 22nd"
checkout master
merge create_login_button
commit "May 29th"
branch fix_user_mapping
checkout fix_user_mapping
commit "June 5th"
checkout master
merge fix_user_mapping

```