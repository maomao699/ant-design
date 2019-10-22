---
order: 6
title:
  zh-CN: 分组
  en-US: Option Group
---

## zh-CN

用 `OptGroup` 进行选项分组。

## en-US

Using `OptGroup` to group the options.

```jsx
import { Select } from 'antd';

const { Option, OptGroup } = Select;

function handleChange(value) {
  console.log(`selected ${value}`);
}

ReactDOM.render(
  <Select defaultValue="lucy" style={{ width: 200 }} onChange={handleChange}>
    <OptGroup label="常用">
      <Option value="军事">Jack</Option>
      <Option value="体育">Lucy</Option>
    </OptGroup>
    <OptGroup label="全面分类">
      <Option value="国际">yiminghe</Option>
    </OptGroup>
  </Select>,
  mountNode,
);
```
