# tweet4Yu

This is a tutorial for Ubuntu

In the project folder:


First, install RVM:

<code>
	sudo apt-get install curl
	curl -L https://get.rvm.io | bash -s stable
	rvm install 2.1.2
	rvm gemset create tweet4yu

	# next line is required every time terminal is open
	rvm use ruby-2.1.2@tweet4yu
</code>

<>

Second, install Bundler:

<code>
	sudo apt-get install bundler
</code>

Third, install gems:

<code>
	bundle install
</code>
