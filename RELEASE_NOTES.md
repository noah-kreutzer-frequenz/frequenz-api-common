# Frequenz Common API Release Notes

## Summary

Update of the `PaginationParams` struct.

## Upgrading

- `PaginationParams` has been changed so that the `page_size` and `page_token`
  fields are now mutually exclusive.

- A new component category `COMPONENT_CATEGORY_HVAC` has been added to the API
  to represent HVAC (Heating, Ventilation, and Air Conditioning) systems.

- Additional information for energy metric

- Add conductor metrics to the proto definitions
