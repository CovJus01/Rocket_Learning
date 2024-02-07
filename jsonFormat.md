## Rough Format of Replay JSON

```
    "content": {
        "body": {
            "caches": [
                {
                    AttributeMapping Objects
                },
                .
                .
                .
                {
                    End of AttributeMapping Objects List
                }
            ],
            "class_mappings": [
                {
                    "name": "className"
                    "stream_id": int
                }
                .
                .
                .
                {
                    End of Class Mapping list
                }
            ],
            "frames": [
                {
                    "delta": float
                    "replications": [
                        {
                            "actor_id": {
                                "limit": int,
                                "value": int
                            }
                            "value": {
                                "spawned": {
                                    "class_name": string,
                                    "flag": boolean,
                                    "initialization": {
                                        "location" {
                                            "bias": int,
                                            "size": {
                                                "limit": int,
                                                "value": int
                                            },
                                            "x": int,
                                            "y": int,
                                            "z": int
                                        },
                                        "rotation": {
                                            "x": float,
                                            "y": float,
                                            "z": float
                                        },
                                       "name": string,
                                       "name_index": int,
                                       "object_id": int,
                                       "object_name": string
                                    }
                                }
                            }
                        }
                    ]
                }

            ]
        }
    }
```
