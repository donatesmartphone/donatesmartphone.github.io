
#### Detailed Tutorial
___
**Step 1** Create Github accounts  

1. Get started by clicking the green "SignUp" button at the top of this page  

2. Enter your signup information as instructed and click "Create an account"  

3. On the second page ("Choose your Plan"), check the box that says "Help me set up an organization"  
![Screenshot](screenshots/signup.jpg?raw=true "Free Nonprofit Starter Template Screenshot")  
4. Follow the remaining steps. Don't forget to confirm your email address.  

___
**Step 2** Fork the repo  

1. Click the "Fork" button at the top of this page

2. When prompted, click the Organization you just set up  

3. Change the name of the repo by clicking "Settings" in the right-hand menu. Name the repo `<orgname>.github.io` (where `<orgname>` is the Organization name you chose for Github) and click "Rename". For example, for us here at Smartergiving, we would name the repo `smartergiving.github.io`.  
![Settings](screenshots/settings.jpg?raw=true "Free Nonprofit Starter Template Screenshot")
4. Your site can now be viewed at `<orgname>.github.io`

___
**Step 3** Enter your organization's info

1. Click the `_config.yml` file  
![SignUp](screenshots/config.jpg?raw=true "Create an Account")  
2. Click the edit button  
![Edit](screenshots/edit.jpg?raw=true "Edit")  

3. Replace the example text with your organization's information  
![Enter Information](screenshots/enter_info.jpg?raw=true "Enter Information")

4. When finished, "commit" the changes by entering a commit message (e.g. "Update config") in the "Commit changes" box at the bottom of the page. Leave the other options as they are, and click the "Commit changes" button.  
![Commit](screenshots/commit.jpg?raw=true "Commit")

5. Preview your site at ` <orgname>.github.io`.
6. Continue to adjust `_config.yml` as needed.

___
**Step 4** Create DonorBox account

1. Go to [DonorBox](https://donorbox.org/orgs/new) and create an account.  
2. We suggest using the "Organization Sign Up" option, which will walk you through creating a [Stripe](https://stripe.com/gallery) account. Stripe handles the actual credit card processing.  
![DonorBox SignUp](screenshots/donorbox_signup.jpg?raw=true "DonorBox SignUp")

3. Follow the prompts to add your first campaign.
4. **Important**: Be sure you fully understand the [risks of accepting online donations](https://donorbox.org/nonprofit-blog/on-fraud-prevention/).  

___
**Step 5** Create TinyLetter account  

1. Go to [TinyLetter](http://tinyletter.com/) and create an account by clicking the "Sign Up Free" button  

___
**Step 6** Enter DonorBox and TinyLetter credentials  

1. Edit the `_config.yml` file and enter your credentials in the appropriate spots

  + **Find your DonorBox campaign name**  
After you've created a campaign, on your dashboard click "edit" for the campaign you'd like to include on your site. 2/3rds of the way down the page you'll see a "Form URL" box. This is where you'll find your Donorbox Username for `_config.yml`  
![DonorBox](screenshots/donorbox.jpg?raw=true "DonorBox")   

  + **Find your TinyLetter username**  
Your TinyLetter Username can be found on your Profile page.  
![TinyLetter](screenshots/tinyletter.jpg?raw=true "TinyLetter")

___
**Step 7** Suggested next steps  

1. Ask for help from your supporters or the open source community.  
    a. [HashtagCharity](https://hashtagcharity.org/charities)  
    b. [Idealist](http://www.idealist.org/add-org)  
    c. [Reddit (/r/nonprofitprojects)](https://www.reddit.com/r/nonprofitprojects)

2. Continue development on your own  
    a. [Set up your local machine](http://ramonaharrison.github.io/jekyll/pixyll/technical/git/github/2015/03/09/how-i-built-my-blog/) (follow steps 1 and 2)  
    b. Download [Github Desktop](https://desktop.github.com/) and [Atom](https://atom.io/) ([tutorial](https://github.com/jwsy/example-website/tree/master#initial-setup))

3. Need Help? Consider attending one of Github's [workshops](http://patchwork.github.io/) or [online trainings](https://training.github.com/classes/)

___
#### Themes
Select an alternative color scheme by changing the `theme:` option in `_config.yml`.  

![Alternative Themes](screenshots/themes.png?raw=true "Alternative Themes")  
___


### TODOs
- [ ] CNAME and custom domain instructions
- [ ] Add cleanup items to tutorial
  - [ ] Delete gh-pages branch
  - [ ] Swap README for a "post-launch" one
- [ ] Open graph metadata
- [ ] Troubleshooting tips

### Future
- [ ] Google Analytics
- [ ] Mailchimp
- [ ] Paypal

___

### License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
