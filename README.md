# Limn &mdash; Fundraising Data

[Limn][limn] is a GUI Visualization Toolkit.  This repository is a set of visualizations relevant to Wikimedia Foundation Fundraising.


## Using with Limn

 * Install [Limn][limn]
 * Link [Limn][limn] to [Limn Fundraising Data][limn_fundraising_data]

```
cd /path/to/limn/../
clone git@github.com:wikimedia/limn-fundraising-data.git
cd /path/to/limn
coke --vardir ./var --data ../../../../limn-fundraising-data --to fundraising link_data
npm start
```

 * Browse the [Limn Datasources Page][limn_datasources]

[limn_fundraising_data]: https://github.com/wikimedia/limn-fundraising-data "Limn Fundraising Data on GitHub"
[limn]: https://github.com/wikimedia/limn "Limn on GitHub"
[limn_datasources]: http://localhost:8081/datasources
