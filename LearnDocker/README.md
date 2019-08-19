# Markdown File

##LEARN Docker!

### TASK: Create simple containarized app that will log into connected volume.

### SOLUTION

To build image type fallowing command being in main directory of the repository:
>docker build -f LearnDocker\Dockerfile -t learndocker:test .

To run container type:
>docker run -d -p 4480:80 learndocker:test