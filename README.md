# Zarate Blog

## To Build

jekyll build

# => The current folder will be generated into ./_site

jekyll build --destination <destination>

# => The current folder will be generated into

<destination>

jekyll build --source <source> --destination <destination>

# => The

<source> folder will be generated into

<destination>

jekyll build --watch

# => The current folder will be generated into ./_site,

# watched for changes, and regenerated automatically.

## To Run Local Server

jekyll serve

# => A development server will run at http://localhost:4000/

# Auto-regeneration: enabled. Use `--no-watch` to disable.

jekyll serve --livereload

# LiveReload refreshes your browser after a change.

jekyll serve --incremental

# Incremental will perform a partial build in order to reduce regeneration time.

jekyll serve --detach

# => Same as `jekyll serve` but will detach from the current terminal.

# If you need to kill the server, you can `kill -9 1234` where "1234" is the PID.

# If you cannot find the PID, then do, `ps aux | grep jekyll` and kill the instance.
