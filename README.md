# App::Able

It's a work in process. If you want to help just create an issue and we will communicate.

Able is a DevOps utility made for simplifying and automate the Agile and DevOps process.

To help on development please begin reading the initial documents under the doc folder. Use Pencil to open the .epgz files and Umbrello to open the .xmi files.

You will find some sheets and standard DevOps material there. Enjoy!

---

App-Able organizes and performs DevOps actions on agile projects.

    Works as a Facade for the 7 modules.

## SINOPSYS

    use App::Able;

    my $plan = App::Able->new();
    $plan->create(
        name => "My Cool Project",
        url => "http://my_repo_url/",
				bots => ['duk','github','docker', 'yo'], 
		);

## BOTS

    Bots are simple shell scripts that:
		- reads some value from stdin
		- perform some action
		- returns some value to stdout

## MODULES

  * Plan
    

  * Create
  * Verify
  * Pack
  * Configure
  * Release
  * Monitor


## SEE ALSO

https://en.wikipedia.org/wiki/DevOps

https://en.wikipedia.org/wiki/DevOps_toolchain
