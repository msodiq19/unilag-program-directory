# unilag-program-directory

This repo provides university of Lagos (Unilag) data in plain JSON. The data contains faculty names, faculty short codes, faculty departments and faculty departments short code. All faculty names and short codes are guaranteed to be unique. Also, all departments name and short codes within a faculty are guaranteed to be unique.

This project will be useful for developers looking to integrate unilag program data into their product

## Install

on it ...

## How do I get started?

Fork and clone the repo

```git clone https://github.com/msodiq19/unilag-program-directory.git```

### Structure

See the `data.json` file in the root folder for the raw data. The JSON is of the form:

```javascript
[
    {
        "facultyName": "Faculty of Arts",
        "facultyCode": "FAT",
        "departments": [
            {
                "departmentName": "Department of English",
                "departmentCode": "ENG",
                "courses": [
                    {
                        "courseName": "English Language",
                        "courseCode": "ENG101",
                        "courseUnit": 3
                    },
                    ...
                ],
                ...
            },
            ...
        ]
        ...
    },
    ...
]
```

## Issues

Feel free to raise an issue on Github if you find a bug or have a feature request.

## Contributing

If you want to contribute to this repository, please refer to the [contributing doc](https://github.com/msodiq19/unilag-program-directory/blob/main/CONTRIBUTING.md).
