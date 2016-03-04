Source for [Made In A2](http://www.madeina2.com/), a directory of startup companies in Ann Arbor, Michigan.

### Company requirements

We've added a few restrictions to keep this a high-quality list:

 - **Technology**: A company's primary product or service must be an information technology product or service.
 - **Traction**: A company must either be publicly launched w/ 1k+ users, be the subject of an article in a national publication, or have raised a round of venture capital.
 - **Location**: A company must have the majority of employees working in Ann Arbor or have a branch with a founder and another full time employee here.

If your company meets the above requirements and you'd like to be added to the list, fork the repo, add your html/css (with your brand colors) and submit a pull request.


### Contributing

Getting started:
 - [Download and install Node.js](http://nodejs.org/) if you haven't already
 - Install Grunt command line tools with `npm install -g grunt-cli`
 - Clone this repo with `git clone https://github.com/sampl/madeina2.git` and `cd madeina2`
 - Run `npm install`. *Note: if `npm install` fails, try `sudo npm install` or do [this](http://stackoverflow.com/questions/16151018/npm-throws-error-without-sudo).*

Run `grunt` to build the site and start a webserver at [localhost:8000](http://localhost:8000/). Install LiveReload to automatically refresh the page when you've made changes.

To deploy, get an `aws.json` file from Sam, add to the project root, and run `grunt deploy`.