# resuable-springboot-workflow

```
job_name:
  uses: shaswattejankar/resuable-springboot-workflow/.github/workflows/build.yml@main
  secrets:
    USERNAME: ${{ secrets.USERNAME }}
    PUBLIC_IP: ${{ secrets.PUBLIC_IP }}
    SSH_KEY: ${{ secrets.SSH_KEY }}
```
