set -o vi
alias baseFilter='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/js/modules/common/baseFilter;ls'

#original: a4:5e:60:d0:90:81
alias getMac='ifconfig en0 |grep ether';

setNewMac() {
    sudo /System/Library/PrivateFrameworks/Apple80211.framework/Resources/airport -z;
    sudo ifconfig en0 ether $(openssl rand -hex 6 | sed 's/\(..\)/\1:/g; s/./0/2; s/.$//');
    networksetup -detectnewhardware;
}

alias actualPackages='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/node_modules/@symphony';
export PHANTOMJS_BIN=/Users/anthon.yzotti/.nvm/versions/node/v5.8.0/lib/node_modules/phantomjs2/bin/phantomjs
alias phantomjs='/Users/anthon.yzotti/.nvm/versions/node/v5.8.0/lib/node_modules/phantomjs2/bin/phantomjs'
alias sendAjax='cd /Users/anthon.yzotti/Desktop/projects/SFE-Login/src/js/modules/authentication/mixins;vim sendAjax.js'
alias dev='git checkout dev'
alias reducers='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/migration/reducers;ls'
alias actions='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/migration/actions;ls'
alias clr='cd ~/Desktop/projects/SFE-Client-App;ls'
alias search='c /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/js/modules/search'
alias goBlast='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/js/modules/common/goBlast;vim index.js'

alias killUglify='git cherry-pick 5b1bb9c'


alias relayManager='cd /Users/anthon.yzotti/Desktop/projects/SFE-Packages/packages/symphony-relay-manager-service/src/js;vim index.js'

alias crypto='cd /Users/anthon.yzotti/Desktop/projects/SFE-CryptoLib-JS/src;gs;ls'
alias cryptoSpec='cd /Users/anthon.yzotti/Desktop/projects/SFE-CryptoLib-JS/spec;gs;ls'
alias km='cd /Users/anthon.yzotti/Desktop/projects/SFE-Packages/packages/symphony-key-manager-service/src/js;vim index.js'
alias grhh='git reset --hard HEAD~1'
alias streams='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/migration/actions/streams;ls'
alias clm='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/migration'
alias imv='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/js/modules/chat;vim imView.js'
alias grh='git reset --hard'
alias lr='cd ~/Desktop/projects/SFE-Login'
alias runtest='PYTHONPATH=. ./env/bin/pybot --variable SELENIUM_HOST:52.0.214.191 --variable SELENIUM_PORT:4444 --variable TESTED_HOST:cip6.symphony.com --variable FILE_UPLOAD_LOCATION:C:\Users\Administrator\Desktop\test.jpg --variable ADMIN_PASSWORD:zl9baSbvVNPvqf20 --variable ADMIN_USERNAME:symphony-engservices+cip6-dev@symphony.com --variable BROWSER:googlechrome --exclude pending --exclude profile --include eula --include ftue --include following --include copying --exclude signals --exclude app_store --outputdir logs --loglevel TRACE --noncritical flaky --exitonfailure tests/ui/web_client'
alias rr='cd /Users/anthon.yzotti/Desktop/projects/SAT-Robot'
alias gpf='git push --force';
alias cl='cd ~/Desktop/projects/SFE-Client-App/src/js'
alias ti='cd ~/Desktop/projects/SFE-Client-App/src/js/modules/common/textInput'
alias cls='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/spec'
alias co='cd ~/Desktop/projects/SFE-Core/src/Symphony/extensions'
alias cor='cd ~/Desktop/projects/SFE-Core'
alias logger='vim ~/Desktop/projects/SFE-Core/src/symphony/extensions/logger.js'
alias bp='vim ~/.bash_profile'
alias packages='cd /Users/anthon.yzotti/Desktop/projects/SFE-Packages'
alias cml='cd /Users/anthon.yzotti/Desktop/projects/SFE-Packages/packages/chat-message-list'
alias ci='cd ~/Desktop/projects/SFE-Client-App/src/js/services;vim copyInterceptor.js'
alias se='cd ~/Desktop/projects/SFE-Client-App/src/js/services;ls'
alias mo='cd ~/Desktop/projects/SFE-Client-App/src/js/modules;ls'
alias chat='cd ~/Desktop/projects/SFE-Client-App/src/js/modules/chat;ls'
alias common='cd ~/Desktop/projects/SFE-Client-App/src/js/modules/common;ls'
alias logs='cd ~/logs'
alias mr='cd /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/js/modules/messageRenderer'
alias gsp='git stash pop'
alias gst='git stash'
alias gsa='git stash apply'

gcb() {
    git checkout -b "$1"
}

gp() {
    git pull "$1" "$2"
}

gc() {
    git checkout "$1"
}

gri() {
    git rebase -i "$1"
}

gcan() {
    git commit --amend --no-edit
}

gcp() {
    git cherry-pick "$1"
}

v() {
    vim "$1"
}

gpud() {
    git pull upstream dev
}

compile() {
    gcc "$1" -o main.out
}

alias ni='npm install'


alias gt='gulp test'
alias gall='git add --all'
alias gcma='git commit --amend --no-edit'
alias gs='git status'
alias gd='git diff'
alias grc='git rebase --continue'
alias gsh='git show'

gcof () {
    git checkout "$1"
}

gcob() {
    git checkout -b "$1"
}

gcp () {
    git cherry-pick "$1"
}

gl () {
    git log -"$1"

}

gcm () {
    git commit -m "$1"
}

alias wtf='gulp browserify:src'

alias qa3='gulp watch --env qa3'
alias qa4='gulp watch --env qa4'
alias qa5='gulp watch --env qa5'
alias qa6='gulp watch --env qa6'
alias qa7='gulp watch --env qa7'
alias qa8='gulp watch --env qa8'
alias qa9='gulp watch --env qa9'
alias corporate='gulp watch --env corporate &'

alias killServer='kill %1'

devTools() {
    gulp watch --env "$1" --devtoolEnabled true --addons "['./bundles/default.json']" --addons-enabled "['./bundles/default.json']"
}

lint () {
  node ~/Desktop/projects/SFE-Client-App/node_modules/.bin/eslint "$1"
}

c () {
  cd "$1";ls
}

l () {
  ls
}

a () {
    ack "$1"
}

unlinkAll() {
    npm unlink symphony-core;
    npm unlink @symphony/chat-message-list;
    npm unlink @symphony/symphony-key-manager-service;
    npm unlink @symphony/symphony-relay-manager-service;
    npm unlink @symphony/message-body;
    npm unlink symphony-cryptolib;
}

linkAll() {
    npm link symphony-core;
    npm link @symphony/chat-message-list;
    npm link @symphony/symphony-key-manager-service;
    npm link @symphony/symphony-relay-manager-service;
    npm link @symphony/message-body;
    npm link symphony-cryptolib;

}

nl() {
    npm link;
}

alias layout="co;vi +/'Layout.prototype.show =' layout.js"

alias app='cl;v app.js'

alias e='exit'
alias mb='c /Users/anthon.yzotti/Desktop/projects/SFE-Packages/packages/message-body'

#compile message-body
alias cmb='mb;npm link;cml;npm link @symphony/message-body;npm link;clr;npm link @symphony/chat-message-list'

alias migration='c /Users/anthon.yzotti/Desktop/projects/SFE-Client-App/src/migration'

#echo kern.maxfiles=65536 | sudo tee -a /etc/sysctl.conf
#echo kern.maxfilesperproc=65536 | sudo tee -a /etc/sysctl.conf
#sudo sysctl -w kern.maxfiles=65536
#sudo sysctl -w kern.maxfilesperproc=65536
#ulimit -n 65536 65536

export NVM_DIR="/Users/anthon.yzotti/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"  # This loads nvm
nvm use v5.8.0
export PHANTOMJS_BIN="/Users/anthon.yzotti/.nvm/versions/node/v5.8.0/lib/node_modules/phantomjs2/lib/phantom/bin/phantomjs"

[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM into a shell session *as a function*

alias clone='rm -rf SFE-Client-App/src;cp -r cloned SFE-Client-App/src'

rc () {
    git checkout rc-current-s$1
}
alias hosts='sudo vim /etc/hosts'
