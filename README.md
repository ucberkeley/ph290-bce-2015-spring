## Prerequisites

The scripts in this repository are designed to be run on a clean installation of the Spring 2015 edition of BCE:

  - [Spring 2015 (BCE-2015-spring.ova)](https://berkeley.box.com/s/2g9x9c3q7qwhb9e4trwc) (3.4GB)
    - (MD5 integrity checksum: 3d26353b7969ebcee6755529ae0751fc)

Read the self-paced installation instructions for details:

  - [http://bce.berkeley.edu/install.html](http://bce.berkeley.edu/install.html)

## Installing system updates specific to PH290

The first time you run these instruction you will need to clone this
repostory from GitHub to your BCE VM. Open a **new** Terminal in BCE and run
these commands:

```bash
git clone https://github.com/ucberkeley/ph290-bce-2015-spring
cd ph290-bce-2015-spring
bash update-ph290-bce-2015-spring
```

To get further system updates you can follow this manual procedure:

```bash
cd ph290-bce-2015-spring
git pull
bash update-ph290-bce-2015-spring
```

## Running the demo

The demo requires the IPython Notebook, RStudio, and several hundred
libraries for processing and analysis installed-- that all comes with
BCE so you don't have to install it yourself!

To set up the demo, simply type:

```bash
bash demo-setup-for-bce-workshop
```

And then run IPython Notebook or RStudio and open the corresponding
folder in your home directory.
