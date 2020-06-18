# Domain management tool
Record domain's expiration date. Inspired by [notes](https://github.com/pimterry/notes).

## Usage

1. Add domain
```bash
domains add example.com
```

2. Remove domain
```bash
domains rm example.com
```

3. Show domain
  - Show all domains, order by expiration date
	```bash
	domains show
	```
  - Show one domain
	```bash
	domains show exmaple.com
	```

4. Update domain
  - Update expired domains
	```bash
	domains update
	```
  - Force update one domain
	```bash
	domains update example.com
	```
