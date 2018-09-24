Would like to apply to a position at Soltius? You came to the right place!

# The Positions

1. Cloud Engineer: check out the `cloud-engineer` [branch](https://github.com/soltius/hiring/tree/cloud-engineer) of this repository.

# Questions

Please provide screenshots and/or code snippets for all steps.

# The Challenge

We would like to see you deploying a two layer application architecture. You have to build everything from scratch, starting from the basics like networking, servers and firewall rules and work your way up to monitoring and log collection.

Then you must develop an app that displays a "Hello New Company!" message using any language/framework/dark magic/spell/sorcery/flavor you like.

## Prerequisites

You can utilize any cloud provider you like to complete this exercise, but we recommend [AWS](http://aws.amazon.com).

Because we do everything in an automated way (OK, almost everything, but anyway...), we'd like to see what you can do managing infrastructure and deploying your app using code. To accomplish this task feel free to use any technology you prefer, e.g.

[Terraform](https://terraform.io)
[Cloudformation](https://aws.amazon.com/cloudformation/)

For monitoring and log collection you can create an account on Datadog.

## Remember

`Don't forget to delete all resources you created as part of this exercise, so you're not billed for them`

# How do I submit my results?

To submit your results to us, follow the instructions below:

### 1. Obtain a current source tree

That step is pretty straight-forward:

`git clone git@github.com:soltius/hiring.git`

### 2. Configure the Mail Sending Options

```
  git config --global sendemail.smtpencryption tls
  git config --global sendemail.smtpserver smtp.gmail.com
  git config --global sendemail.smtpuser yourname@gmail.com
  git config --global sendemail.smtpserverport 587
  git config --global sendemail.smtppass hackme
  git config --global sendemail.suppresscc self
```

### 3. Configure the Default Destination Address

`git config sendemail.to hiring-<branch_name>@soltius.io`

PS.: replace <branch_name> with the branch name you cloned from the
upstream repo. For instance: If you have cloned the ```cloud-engineer```
branch then the email must be ```hiring-cloud-engineer@soltius.io```.

### 4. Describe your changes

Describe your changes in imperative mood, e.g. "make xyzzy do frotz" instead of "[This patch] makes xyzzy do frotz" or "[I] changed xyzzy to do frotz", as if you are giving orders to the codebase to change its behaviour.
`It is paramount that you submit a single patch, if you send multiple patches (or "multiple commits") then your submission won't be reviewed.`

### 5. Submit your patch

`git send-email -1 --subject-prefix="<YourName> <PositonApplied> interview"`
