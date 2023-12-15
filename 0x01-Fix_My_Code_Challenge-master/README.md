# Fix my code 1

> 
Fix my code is a new type of project, where we’ll jump into an existing code base and fix it!

Sometime you will know the language, sometime not.

Please download the repository [0x01-Fix_My_Code_Challenge](https://intranet.alxswe.com/rltoken/H1D38vm3qtejhlFTuoxUrA) and use it as initial files for all solutions.

You should not recode everything, just fix it!

## Advanced tasks

- `status-server` - I just started a new Flask project and the first thing I’m putting in place is a route for the status of my API (super important for a load balancer implementation).
But I don’t know why it’s not working…
Could you look at it and fix it please?

```bash
$ python -m api.v1.app 
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
$ curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
$
```

