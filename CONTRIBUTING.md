# CONTRIBUTING

## Main Webpage HTML and deployed websites

In FChart on GitHub, there are 2 types of forks:

* **Main Webpage**: it is the source code of the FChart, but does not include the charts. It's because each time we update the chart, the size of the repo goes up. To prevent each time we need to clone this GitHub repo, and also start focusing on proving the source code only.
* **FChart Deployments**: it is the FChart source code, but included the charts in there. It can only be used to deploy the FChart web application on the GitHub page and/or other places.

Mostly, the "Main Webpage" forks are named with `master` and/or name with the tasks in [Issues](https://github.com/shiroinekotfs/FChart/issues), or even the name `master-XXXX`. You can try to view the fork graph when you clone this GitHub repo.

When a FChart is deployed, it mainly uses the form name: `fchart-airac-XXXX` where `XXXX` is the [Cycle Dates](https://ww2.jeppesen.com/update-cycle-and-effective-dates-schedule/)

## Demoting older versions and updating the FChart

You need to make sure that the FChart newer fork is named correctly and ready to be deployed.

Once it's done, you can change the deployed fork, re-update it, demote the older fork then delete it.
