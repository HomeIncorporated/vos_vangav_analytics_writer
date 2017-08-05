
> **why?** vangav analytics is a [vangav backend](https://github.com/vangav/vos_backend) template covering: service oriented architecture and multi-entry-point api; this is also the analytics service used by all vangav's products

# vangav analytics writer

+ [vangav analytics writer](https://github.com/vangav/vos_vangav_analytics_writer) and [vangav analytics reader](https://github.com/vangav/vos_vangav_analytics_reader) services work together and are generated using [vangav backend](https://github.com/vangav/vos_backend)

## prerequisite

+ [vangav backend tutorials](https://github.com/vangav/vos_backend)

## functionality

### [vangav analytics writer](https://github.com/vangav/vos_vangav_analytics_writer)

+ handles writing analytics

### [vangav analytics reader](https://github.com/vangav/vos_vangav_analytics_reader)

+ handles reading actions in various ways (e.g.: by year, by day, by category, ...)

### action structure

+ [actions.json](https://github.com/vangav/vos_vangav_analytics_writer/blob/master/conf/setup_data/actions.json) in both services define how analytics are structured

+ here's a simple example

```json
  {
    "categories": [
      {
        "category_name": "page_views",
        "category_name_short": "PV"
      }
    ],
    "action_classes": [
      {
        "class_name": "backend_page_views",
        "class_prefix": "BPV",
        "class_wide_categories": [
          "PV"
        ],
        "action_ids": [
          {
            "action_id": "quick_start",
            "action_categories": []
          }
        ]
      }
    ]
  }
```

| element | explanation |
| ------- | ----------- |
| []() |  |
| []() |  |
| []() |  |
| []() |  |
| []() |  |
| []() |  |
| []() |  |
| []() |  |
| []() |  |
| []() |  |


























