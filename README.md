# Laravel Two-Factor Auth via Email

Simple demo-project to add two-factor authentication, with sending 6-digit unique verification code via email.

Every time user logs in, they will see this view, with ability to re-send the code:

![Laravel two-factor authentication form](https://laraveldaily.com/wp-content/uploads/2019/10/Screen-Shot-2019-10-05-at-7.46.50-PM.png)

At the same time, this email will be sent:

![Laravel two-factor authentication email](https://laraveldaily.com/wp-content/uploads/2019/10/Screen-Shot-2019-10-05-at-7.46.18-PM.png)


---

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there, also email provider settings (to send verification codes)
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel with default credentials __admin@admin.com__ - __password__

## License

Basically, feel free to use and re-use any way you want.

---

