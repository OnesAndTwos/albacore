# Welcome to the Albacore project.

Albacore is intended to be a professional quality suite of Rake tasks to help automate the process of building a .NET based system. All tasks are built using a test-first approach through rspec, and all tests are included in the Albacore gem.

## How To Install Albacore From Github Gems:

If you would like to install the current, stable release of Albacore, you can do so easily through the Github Gems server. Follow these simple instructions and you will be good to go.

**Step 1:** Setup github as a gem source

> `gem source -a http://gems.github.com`

(note: you only need to do this once for any given computer that is going to install gems from github.)

**Step 2:** Install the Albacore gem

> `gem install derickbailey-Albacore`

## How To Manually Build And Install The Albacore Gem

If you would like to install the latest source code for Albacore, and get all the new features and functionality (possibly in an unstable form), you can manually build and install the Albacore gem. Follow these simple instructions and you will be good to go.

**Step 1:** Clone Albacore

Use your Github account to fork Albacore, or clone it directly from my public clone URL.

> `git clone git://github.com/derickbailey/Albacore.git Albacore`

**Step 2:** Build the gem

In your local clone of Albacore, use the gem build command to build the latest version of the Albacore code into a gem.

> `gem build Albacore.gemspec`

this will produce an 'Albacore-#.#.#.gem' file, where '#.#.#' is the version number. For example 'Albacore-0.0.1.gem'.

**Step 3:** Install the gem

After building the gem, you can install it from your local file system.

> `gem install -l Albacore-#.#.#.gem`

where '#.#.#' is the version number of the gem. For example 'Albacore-0.0.1.gem'

## How To Use Albacore

After installing Albacore, you only need to

> `require 'albacore'`

in your rakefile. This will allow you to use the tasks that Albacore includes. Beyond the simple require statement, check out the [Albacore Wiki](http://wiki.github.com/derickbailey/Albacore) for detailed instructions on how to use the built in tasks and their options.