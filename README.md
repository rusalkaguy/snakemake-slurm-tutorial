# snakemake-slurm-uab
Working example of snakemake tutorial using UAB Cheaha computing cluster via SLURM scheduler

Use with Snakemake tutorial at http://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html

In this setup, one runs "snakemakeslurm" instead of "snakemake" and it pulls in the cluster config file and creates the sbatch commandline mapping. Surely there is a more elegant way to do this!

Basic flow

	source ~/snakemake-miniconda3/bin/activate snakemake-tutorial
	snakemakeslurm 

