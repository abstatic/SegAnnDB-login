# SegAnnDB-login

This repository is a clone of original [pyramid_google_login](https://github.com/ludia/pyramid_google_login)

It contains modifications done in code to make it work with SegAnnDB

**Approach - **

`pyramid_google_login` does not handle any kind of authentication policy by itself. It only helped in fetching the
user profile details from google. I made a workaround, now it sets a cookie in the response which is equivalent to the user_id
(email)

Some bugs were also fixed, turns out the original version did not work with the a latest version of pyramid anymore, so a 
couple bugs were fixed as well.

**On pypi -**

This package will be uploaded to pypi as well, under the same name.
