# [Benjamin Lo](https://bebit-inc.esa.io/members/benjamin_lo)

### Benjamin Lo
A Software Engineer currently working on [USERGRAM](https://www.bebit.co.jp/usergram/) at [bebit, Inc](https://github.com/bebit). Currently trying to level up to be a Senior Developer.

### GET Basic profile request

Invoking the `get_profile(..)` function calls the API endpoint `https://benjamin_lo.io/api/profile/6195689/` in the background.

```python3
import benjamin_lo
# ...
benjamin_lo.get_profile()
```

Sample response as JSON

```json
"basic_info": {
    "id": 6195689,
    "full_name": "Benjamin Lo",
    "nationality": "British",
    "profession": "Full Stack Engineer",
    "years_of_experience": 6
}
```

## GET Technologies & experience request
Invoking the `get_experience(..)` function calls the API endpoint `https://benjamin_lo.io/api/profile/6195689/technologies/` in the background.

```python3
import benjamin_lo
# ...
benjamin_lo.get_experience()
```
Sample response as JSON
```json
"technologies": {
    "frontend": ["React.JS", "Vue.JS"],
    "backend": ["Django", "DRF", "Laravel", "MySQL", "Ruby On Rails"],
    "devops": ["docker", "kubernetes", "AWS Athena", "AWS Lambda", "AWS DynamoDB"]
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
