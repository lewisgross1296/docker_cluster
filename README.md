# docker_cluster
A repository for creating docker files to be used on the CHTC HPC

# build instruction
# docker build -t user_name/image_name:tag_name . (. is technically path to directory containing Dockerfile)
# if no tage is used, the tag latest will be applied to the image with the most recent build
docker build -t ligross/frensie_hpc:frensie_stable .

# run instructiuns

# push instructions
docker push ligross/frensie_hpc:frensie_stable