# My bash configuration and installations 

Add this to your `.bash_profile` file

```bash
for f in ~/.my-bash/*.include.sh; do
   source "$f"
done
```