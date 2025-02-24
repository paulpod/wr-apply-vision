Note this is prototype code. Not intended for production use.

Get up and running in 5 minutes

Clone this repo using git clone ```[repo_Github_URL] [local_dir]```

Move into the local copy ```cd [local_dir]```

Add all the ingredients ```npm install```

Run it ```npm run dev```

Look at it in your browser ```http://localhost:3000/```

You’ll probably want to detach from this repo to create your own at this point, so use ```git remote rm origin``` to remove this repo and and either create a new one on github.com in a browser or use gh repo create - once you've done that use git remote add origin https://github.com/username/my-new-repo.git to add it as a new remote for your prototype. Now do a quick git push origin main and you‘ll see the contents of your new prototype fill the empty repo. Good job!
Make a branch ```git checkout -b myFeature```

Do some work. You can find some examples on this page ```http://localhost:3000/examples```

Happy? Make a ```commit git add .``` and ```git commit -m "new feature is cool"```

Push your work to github ```git push origin myFeature```

Merge it on github

Put it somewhere so other people can look at it ```heroku create``` and

```git push heroku main``` all done!

Everyone happy? Switch back to main git checkout main and tidy up ```git branch -D myFeature```

Don't forget to ```git pull``` to get your changes back into your local repo

Troubleshooting

No git? Install Xcode tools from Apple

Error seeing the repo on github? You probably need to install Github CLI tools and login. Use ```brew install gh``` and then ```gh auth login``` and input the verification code from the terminal on the web.

No grunt? Install with ```brew install grunt```

No brew? Install from https://brew.sh
