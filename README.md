# Year4000 Locales

Theses are the translations that we use in our applications.
Inside each of the folders is a `locales.json` this is the
list of all enabled locales that can be used. Within the
`locales.json` in the folders will tell the system to load
addition locales as modules. They are noted by a prefix `/`.
All refrences must be an absoule path to the directory
containing another `locales.json`.


## Loading

The `master` branch is what the production servers will see.
Any changes that are made in `master` will take time to fully
be deployed, as all server messages are cached and will update
when their cache expires.

Base url to load the locales within the applications.
> https://year4000.github.io/Locales/
