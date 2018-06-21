Server IP Address: 18.179.5.98
Port Number: 2200
URL: 18.179.5.98.xip.io/catalog/homepage
Software installed: APACHE POSTGRESQL GIT python-pip
Configuration made:
   Step1: Change the ssh default port on the Lightsail Instance Manage page
   Step2: make a new user 'grader' on server
   Step3: use ssh-keygen on my local machine to generate public key and private key
   Step4: copy public key to .ssh/authorized_keys on server
   Step5: use private key to log in (by supplying the i option) 
   Step6: configure apache using WSGIScriptAlias directive to mount my application at root of the server
   Step7: enable mod_wsgi
   Step8: start apache, iteratively test and debug
Private Key passphrase: LinuxServerConfiguration
-----BEGIN RSA PRIVATE KEY-----
Proc-Type: 4,ENCRYPTED
DEK-Info: AES-128-CBC,BAF2C993AC738F6D08CE7DDC1DAFB544

JZFH/qqfjdkBBOCcsE0qobYnWI1UXbu6JckW1YdxJ5pY6lQGg+pfmbKpx/+oPfmJ
LyENVzLJHETlgZPVbH/TOJ89rq6S21dH+qZOtBnLCQwgshKL574tNFaw3Y0k8O6u
Pz9g7wfrF9rNYJzcCXsW/e4D7krC1irxbLjKF1ttYiroEzhWcwNO9o6kQHEaG5yR
ofCTcet0uL+E0jzjPSMn4/vVF5+CNn0yYr7f3lCeuFOO9FITGNl39XxDxaSq3CZI
gsQdIbtXMUWGKUdj6mkVKBa8qGYCp3uPIo9aeCxvzf4E/6F8k/OceM10u7p2Y5WP
YiFrMfYkbfveVWJFLWlpR3jeQq9+ENOmzxw56AVFx2OK9WCEv7l1bNQCGLPg5bU4
s056G6hXizJ8m0611vyzxQ/9+yhPeB5rSi/b2R1PmxX9/uN2cGhQ6TMrpSr79p8n
2k57vqvbL+7sL31mtC9d26qPTU26K6XQD8bYjwZEweBrkmcanQF4JBg+0lV4SJTq
YUNQ1EhC3qJCKf++F8W5Iweiy+2+cllk8/Rzf7ykKBd48SUkHNZV0RMIfmMHjAtu
kvL05+ZMkxoRHeGug8spYzg4ddKU9VmqVKWkwQRSv5BLMPHueZ5Qx5S00z3zsWS9
2lEGuVLZ11goVIyM+6IPlRjz7lTB7OaoHb5NoVv9V4J7eet12dFbZI63mPm8zDKv
RxlrEsz2DFinbiaklIQQyNQ72iuy2qK5ubzm3Jy6f4PVMZ14JPqEQGDL7kKxLt35
HWzELLRqLf2u0zjWzGc90sP8RDWmTciRbaBfT0kg6e7+f2qZGHIknxvk3hvv9tFG
MxbrJNqPHl0MXJo+5aRTV5qdBX5McYYMlIjyvGWpivx+JtSGvH6pUcNefTZs/QF3
I8YgF9kCJQfonMgpfEvMW63RqvVwVw8bIy1nmYvNs2lQDM3A0aeWRfY3Wr2HP3j3
t9LAcPBhydQmrBiYo0fUdg8hwLjMf8LuYwP37DqXYrRElKoMsAqnXZvRzZ/TsRcZ
iGjWBcJrFE2QVoZZZsKb0aoTtAWxcmzPfAt0rnXZ5sue3UjIKbTO39uwIiER4OxH
5EpnXEtiUt8JMkhGaL7ciZVtHR1Pm3kbnJGxEhbLI0PvvmZ1ddTJvpgO8ZY2p+ov
2iV7/GxE+QOLKjqv1x5RI3ZnoVNIXUhdTjWirvdfKxjTzDvX0kZ43R2ooZLnX4RP
iQo82bFvW+51EScM8hC2SABMreabidO6bxWEDZ9nAgvTIre9xPMc+TO9HEaxtMhv
qQp4reuOQwIJ6/WuiNc76ISQ+d6VwTSS79px+RSvxMqtZYnm4703BH4pgOFb3Oho
nA7dKihP4/z1FhUNcVQ1Z3ALxgSDnduCrTn2iVWjONFdFOYrPjeMmJJmJJdUvQWB
j6Sa+kP4pdyk7SY7Y1yHz0TxDCl/YYCiY9SIrRTcTsFe/2Wj8Lxo0wBo1l6EPbmX
ytSPmLvDsWMwKdBv5NqZkqVj7ePadezhxyMlJcBwFlFBRPqFsZznIuj/us33m2qh
hR7DDAqbWh0yZoyB9weB+B9dPuoDpUi3kY8tlcZH6mMjZmYw2onO8l3oS6i3ePk3
-----END RSA PRIVATE KEY-----

Note: In my previous attempts, I did insert my private key and passphrase in the Notes To Reviewer field. But for some reason, my previous reviewers all can't see my notes. So I decided to put them in my readme
