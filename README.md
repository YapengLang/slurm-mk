# slurm-mk
Make slurm jobs and folders easy to manage.

Credits: logic @YapengLang, script& doc @Claude.Sonnet4.6

Basic usage (with defaults):

```bash
bash smake.sh -j my_assembly -l /scratch/logs -o /scratch/results
```

Override any SLURM resource:

```bash
bash smake.sh -j my_assembly -l /scratch/logs -o /scratch/results \
  -c 16 -m 64GB -t 12:00:00 -p highmem
```

Have fun.
