Object class method
public boolean equals(Object o)
Returns true --- If 'this' (invoker ref) & o ---refers to the same object(i.e reference equality) i.e this==o , otherwise returns false.

Need of overridng equals method ?
To replace reference  equality by content equality , based upon prim key criteria.

eg : In Car scenario 
(Primary key -- int registration no)

In Account scenario -- 
composite primary key --based upon branch code & account id.

In Customer scenario -- email 


