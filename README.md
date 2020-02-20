# JListsUtils

Oh, lists filters are so cool..let's use them

```Java
List<Customer> customersWithMoreThan100Points = customers
  .stream()
  .filter(c -> c.getPoints() > 100)
  .collect(Collectors.toList());
```

Seriously, Java???

This is how I like it:

```Java
List<Customer> customersWithMoreThan100Points = Lists.filter(customers, c -> c.getPoints() > 100);
```

Yes, I don't like docs.
