# why ubuntu is not that good.
This is based on my personal opinions/experiences and what i have read on the internet

## Canonical
Canonical has started making questionable decisions which go against why a lot of users use Linux and open source, that is freedom of choice.    
For example forcing pre-installed amazon shop application, most users were against this but Canonicals commercial interests required it.
Eventually it did get removed but before that it went so far that the distro was taken as [spyware](https://www.gnu.org/philosophy/ubuntu-spyware.en.html).  
Canonical is now also more focused on profit than anything else, which is indicated by Canonical starting projects such as the Unity desktop environment and then cancelling it when it didn't make enough money.  
In general canonical has also tried to replace essential fundamental tools in linux to impose its own such as the graphical server, the boot system, and desktop environment and of course Snap

## snap packages
Since snap packages are containerized they can have issues with theming and changing the system itself.  
Snap packages are also much slower than native packages because they are actually compressed filesystem images that need to be mounted before being executed.  
Snap packages dont have dependencies because they always include the needed dependencies and are thereby also much larger than native packages.  
Canonical also tries to force snap packages on the users by always preferrring snap packages over dpkg packages.  
Many people leave proprietary operating systems to get away from such behaviour.  
The repository backend for snap packages is also proprietary which is again the sort of behaviour because of which some people switched away from proprietary operating systems.  
Because of the closed source backend snap packages dont go through checks and reviews by the community which may make them less secure (but may also not difficult to tell)


## package mess
The desktop environment used is GNOME which is fine and all, however in the latest ubuntu version as of writing this is 22.04 here the gnome desktop environment is
a mess of packages from different gnome versions for example it has the gnome 42 base packages and the gnome calculator from version 41 and the keyring from version 40  
This may also indicate that Canonical has refocused their efforts on the server version which is the version that generates most of the companies revenue.  

