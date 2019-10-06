stage(fetch lastest)
- git (plugin)
stage(build)
- sh (cd $DIR; mvn install)
stage(post build)
- path you want to store the artifact (plugin artifact)
stage(deploy)
- server/container?
- sh (cp artifact; permission to the run executable; java code.jar)
