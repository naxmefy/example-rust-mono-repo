# Roadmap

This is a simple project roadmap.
It just lists some base features planned for some version.

It should show a simple development progress.

## Kick off

- [ ] simple pages
- [ ] user account
    - [ ] profiles `/{username}`
    - [ ] settings `/{username}/settings`
    - [ ] profile settings `/settings/profile`
- [ ] organisation account
    - [ ] profiles `/{orgname}`
    - [ ] settings `/{orgname}/settings`
    - [ ] profile settings `/{orgname}/settings/profile`

## v1.0.x

- [ ] a simple homepage with infos about the product at root path `/`
    - [ ] simple ssr from template engine
- [ ] user accounting
    - [ ] sign up
        - [ ] `GET /signup` for the page
        - [ ] `POST /signup` to execute action
        - [ ] Mail Address (unique)
        - [ ] Username (unique)
        - [ ] Password
    - [ ] sign in
        - [ ] `GET /login` for the page
        - [ ] `POST /login` to execute action
        - [ ] Username or Mail Address
        - [ ] Password
    - [ ] sign out
        - [ ] `GET /logout` for the page
        - [ ] `POST /logout` to end the session
    - [ ] simple profile
        - [ ] `GET /{username}` for the profile page of an user

## v1.1.x

- [ ] mailing / mail templates
- [ ] user accounting
    - [ ] verify mail address
        - [ ] `GET /verify-mail-address` to verify mail address
        - [ ] `POST /resend-mail-address-verification`
    - [ ] forgot password
        - [ ] `GET /forgot-password` for the page
        - [ ] `POST /forgot-password` to execute action
        - [ ] Mail Address
        - [ ] Sends recovery if mail address is known
- [ ] simple contact form
    - [ ] `GET /contact`
    - [ ] `POST /contact`
    - [ ] Mail Address (if not logged-in)
    - [ ] Message
    - [ ] Checkbox to receive a copy
