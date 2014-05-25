rails-environment-setup
=======================
Complete this activity by following the instructions to set up your development environment and commenting below with a note to say whether you're using a Mac, Windows or Linux.

# Download and Install Sublime Text 3

This is a great text editor which makes coding easier. It completes code for us, colours it(syntax highlighting) and many other tricks.

[<span style="background-color: rgb(255, 255, 0);">Download from here</span>](http://www.sublimetext.com/3)

# Install Rails

This can be tricky but it can also be easy. We'll just have to wait and see how it turns out for you.

## For Mac

1.  Check you have Command Line Tools installed

In your terminal, type `xcode-select --install`

![](https://www.openlearning.com/courses/BeginnerCoder/Activities/134SetupRvmRubyAndRails/Screenshot2014-02-1508.20.47.png?action=download)

1.  Check that it is working

In your terminal, type `gcc --version`

![](https://www.openlearning.com/courses/BeginnerCoder/Activities/134SetupRvmRubyAndRails/Screenshot2014-02-1508.21.34.png?action=download)

1.  Install HomeBrew

    ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

When that finishes, run `brew doctor`

1.  Install RVM

In your terminal paste:

    \curl -sSL https://get.rvm.io | bash -s stable

1.  Install the latest Ruby

In your terminal type:

    rvm install 2.1.0

Check your version of Ruby anytime by typing:

    ruby -v

1.  Install Rails

In your terminal type:

    rvm use ruby-2.1.0@rails-411 --create

Now install the latest Rails:

    gem install rails

When it's finished, check the version with `rails -v`. It should be 4.1.1

Now set this as the default gemset:

    rvm use ruby-2.1.0@rails-411 --default

## For Linux

[RailsApp instructions](http://railsapps.github.io/installrubyonrails-ubuntu.html)

## For Windows

This is the trickiest of all but not impossible.

Here are your options:

New: [RailsFTW](http://railsftw.bryanbibat.net/)

[RubyInstaller.org ](http://rubyinstaller.org/downloads/)

-- Download and install [Ruby version 1.9.3](http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-1.9.3-p545.exe?direct)

-- Download and install the [Development Kit for 1.9.3](https://github.com/downloads/oneclick/rubyinstaller/DevKit-tdm-32-4.5.2-20111229-1559-sfx.exe)

-- Install Rails from the Command Line with Ruby app 

    <span style="background-color: rgb(255, 255, 255);">gem install rails --version=4.0.4 --no-ri --no-rdoc</span>

Other options:

[Railsbridge - Vagrant](https://github.com/railsbridge-boston/railsbridge-virtual-machine) (Using a virtual machine, a popular choice with my other students on Windows)

[Step-by-step videos direct to machine](http://www.globalnerdy.com/2013/10/25/how-to-install-rails-4-on-windows-including-windows-8-and-8-1/) (a little complicated but if it works for you it's the best solution)

[Nitrous.io](https://www.nitrous.io/) (online cloud solution - need good internet connection)

Other options for Windows users are dualbooting with Linux or using a Linux virtual machine as your dev environment.
