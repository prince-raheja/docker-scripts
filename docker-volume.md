Docker volume

Docker run -v {container_dir_intact} -v {local_dir}:{container_dir} {image_id}

{container_dir_intact} -> directory that should be used as it is inside container

{container_dir} -> points to {local_dir} and will fetch contents from there
