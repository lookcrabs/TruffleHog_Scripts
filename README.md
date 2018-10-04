# TruffleHog_Scripts
A wrapper script around trufflehog to dump finds to a json file and later check against that file. Hopefully can be integrated into travis-ci or jenkins to alert on possible secrets. 

Slowly growing into a huge mess. Will probably rewrite trufflehog to remove that dependency. Trufflehog uses pythonGit which calls subprocess.Popen(git-blah). I think it would be better to use some kind of api if possible. BLAH
