# eclipse.collections Skill

Use this skill to work with Norm module `eclipse.collections` version 4. Use only declarations listed below.

## `eclipse.collections`

Source: `AbstractRichIterable.norm`

### `AbstractRichIterable`

```norm
class AbstractRichIterable<T> implements RichIterable<T>
```

Type parameters:

- `T`

#### `AbstractRichIterable`

```norm
AbstractRichIterable(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections`

Source: `FastList.norm`

### `FastList`

```norm
class FastList<T> extends AbstractMutableList<T> implements Externalizable, RandomAccess, BatchIterable<T>, MutableList<T>, MutableCollection<T>, RichIterable<T>
```

Type parameters:

- `T`

#### `FastList`

```norm
FastList(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `add`

```norm
Void add(Integer arg0, T? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `T?`

Returns: `Void`

#### `add`

```norm
Boolean add(T? arg0)
```

Parameters:

- `arg0`: `T?`

Returns: `Boolean`

#### `allSatisfy`

```norm
Boolean allSatisfy(Function<Boolean(T?)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(T?)>?`

Returns: `Boolean`

#### `anySatisfy`

```norm
Boolean anySatisfy(Function<Boolean(T?)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(T?)>?`

Returns: `Boolean`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `collect`

```norm
FastList<V>? collect<V>(Function<V?(T?)>? arg0)
```

Type parameters:

- `V`

Parameters:

- `arg0`: `Function<V?(T?)>?`

Returns: `FastList<V>?`

#### `contains`

```norm
Boolean contains(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `count`

```norm
Integer count(Function<Boolean(T?)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(T?)>?`

Returns: `Integer`

#### `get`

```norm
T? get(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `T?`

#### `getFirst`

```norm
T? getFirst()
```

Returns: `T?`

#### `getLast`

```norm
T? getLast()
```

Returns: `T?`

#### `groupBy`

```norm
FastListMultimap<V, T>? groupBy<V>(Function<V?(T?)>? arg0)
```

Type parameters:

- `V`

Parameters:

- `arg0`: `Function<V?(T?)>?`

Returns: `FastListMultimap<V, T>?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `noneSatisfy`

```norm
Boolean noneSatisfy(Function<Boolean(T?)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(T?)>?`

Returns: `Boolean`

#### `reject`

```norm
FastList<T>? reject(Function<Boolean(T?)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(T?)>?`

Returns: `FastList<T>?`

#### `remove`

```norm
T? remove(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `T?`

#### `remove`

```norm
Boolean remove(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `reverseThis`

```norm
FastList<T>? reverseThis()
```

Returns: `FastList<T>?`

#### `select`

```norm
FastList<T>? select(Function<Boolean(T?)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(T?)>?`

Returns: `FastList<T>?`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `sortThis`

```norm
FastList<T>? sortThis()
```

Returns: `FastList<T>?`

### `fastListNew`

```norm
FastList<T> fastListNew<T>()
```

Type parameters:

- `T`

Returns: `FastList<T>`

## `eclipse.collections`

Source: `FastListMultimap.norm`

### `FastListMultimap`

```norm
class FastListMultimap<K, V> extends AbstractMutableListMultimap<K, V> implements Externalizable, MutableListMultimap<K, V>, MutableMultimap<K, V>, Multimap<K, V>
```

Type parameters:

- `K`
- `V`

#### `FastListMultimap`

```norm
FastListMultimap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `containsKeyAndValue`

```norm
Boolean containsKeyAndValue(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `notEmpty`

```norm
Boolean notEmpty()
```

Returns: `Boolean`

#### `put`

```norm
Boolean put(K? arg0, V? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`

Returns: `Boolean`

#### `remove`

```norm
Boolean remove(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `sizeDistinct`

```norm
Integer sizeDistinct()
```

Returns: `Integer`

### `fastListMultimapNew`

```norm
FastListMultimap<K, V> fastListMultimapNew<K, V>()
```

Type parameters:

- `K`
- `V`

Returns: `FastListMultimap<K, V>`

## `eclipse.collections`

Source: `IntArrayList.norm`

### `IntArrayList`

```norm
class IntArrayList extends AbstractIntIterable implements MutableIntList, Externalizable, IntIterable
```

#### `IntArrayList`

```norm
IntArrayList(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `add`

```norm
Boolean add(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `allSatisfy`

```norm
Boolean allSatisfy(Function<Boolean(Integer)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(Integer)>?`

Returns: `Boolean`

#### `anySatisfy`

```norm
Boolean anySatisfy(Function<Boolean(Integer)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(Integer)>?`

Returns: `Boolean`

#### `binarySearch`

```norm
Integer binarySearch(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `contains`

```norm
Boolean contains(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `count`

```norm
Integer count(Function<Boolean(Integer)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(Integer)>?`

Returns: `Integer`

#### `get`

```norm
Integer get(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `getFirst`

```norm
Integer getFirst()
```

Returns: `Integer`

#### `getLast`

```norm
Integer getLast()
```

Returns: `Integer`

#### `max`

```norm
Integer max()
```

Returns: `Integer`

#### `min`

```norm
Integer min()
```

Returns: `Integer`

#### `reject`

```norm
IntArrayList? reject(Function<Boolean(Integer)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(Integer)>?`

Returns: `IntArrayList?`

#### `reverseThis`

```norm
IntArrayList? reverseThis()
```

Returns: `IntArrayList?`

#### `select`

```norm
IntArrayList? select(Function<Boolean(Integer)>? arg0)
```

Parameters:

- `arg0`: `Function<Boolean(Integer)>?`

Returns: `IntArrayList?`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `sortThis`

```norm
IntArrayList? sortThis()
```

Returns: `IntArrayList?`

#### `sum`

```norm
Long sum()
```

Returns: `Long`

### `intArrayListNew`

```norm
IntArrayList intArrayListNew()
```

Returns: `IntArrayList`

## `eclipse.collections`

Source: `UnifiedMap.norm`

### `UnifiedMap`

```norm
class UnifiedMap<K, V> extends AbstractMutableMap<K, V> implements Externalizable, BatchIterable<V>, MutableMap<K, V>, MutableMapIterable<K, V>, MapIterable<K, V>, RichIterable<V>
```

Type parameters:

- `K`
- `V`

#### `UnifiedMap`

```norm
UnifiedMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `get`

```norm
V? get(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `V?`

#### `getIfAbsentPut`

```norm
V? getIfAbsentPut(K? arg0, V? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`

Returns: `V?`

#### `getIfAbsentPut`

```norm
V? getIfAbsentPut(K? arg0, Function<V?()>? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Function<V?()>?`

Returns: `V?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `keySet`

```norm
JavaSet<K>? keySet()
```

Returns: `JavaSet<K>?`

#### `put`

```norm
V? put(K? arg0, V? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`

Returns: `V?`

#### `removeKey`

```norm
V? removeKey(K? arg0)
```

Parameters:

- `arg0`: `K?`

Returns: `V?`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `values`

```norm
Collection<V>? values()
```

Returns: `Collection<V>?`

### `unifiedMapNew`

```norm
UnifiedMap<K, V> unifiedMapNew<K, V>()
```

Type parameters:

- `K`
- `V`

Returns: `UnifiedMap<K, V>`

## `eclipse.collections`

Source: `UnifiedSet.norm`

### `UnifiedSet`

```norm
class UnifiedSet<T> extends AbstractUnifiedSet<T> implements Externalizable, MutableSet<T>, Pool<T>, BatchIterable<T>, MutableCollection<T>, RichIterable<T>
```

Type parameters:

- `T`

#### `UnifiedSet`

```norm
UnifiedSet(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `add`

```norm
Boolean add(T? arg0)
```

Parameters:

- `arg0`: `T?`

Returns: `Boolean`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `contains`

```norm
Boolean contains(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `remove`

```norm
Boolean remove(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

### `unifiedSetNew`

```norm
UnifiedSet<T> unifiedSetNew<T>()
```

Type parameters:

- `T`

Returns: `UnifiedSet<T>`

## `eclipse.collections.collection.mutable`

Source: `collection/mutable/AbstractMutableCollection.norm`

### `AbstractMutableCollection`

```norm
class AbstractMutableCollection<T> extends AbstractRichIterable<T> implements MutableCollection<T>, RichIterable<T>
```

Type parameters:

- `T`

#### `AbstractMutableCollection`

```norm
AbstractMutableCollection(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.list.mutable`

Source: `list/mutable/AbstractMutableList.norm`

### `AbstractMutableList`

```norm
class AbstractMutableList<T> extends AbstractMutableCollection<T> implements MutableList<T>, MutableCollection<T>, RichIterable<T>
```

Type parameters:

- `T`

#### `AbstractMutableList`

```norm
AbstractMutableList(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.map`

Source: `map/AbstractMapIterable.norm`

### `AbstractMapIterable`

```norm
class AbstractMapIterable<K, V> extends AbstractRichIterable<V> implements MapIterable<K, V>, RichIterable<V>
```

Type parameters:

- `K`
- `V`

#### `AbstractMapIterable`

```norm
AbstractMapIterable(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.map.mutable`

Source: `map/mutable/AbstractMutableMap.norm`

### `AbstractMutableMap`

```norm
class AbstractMutableMap<K, V> extends AbstractMutableMapIterable<K, V> implements MutableMap<K, V>, MutableMapIterable<K, V>, MapIterable<K, V>, RichIterable<V>
```

Type parameters:

- `K`
- `V`

#### `AbstractMutableMap`

```norm
AbstractMutableMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.map.mutable`

Source: `map/mutable/AbstractMutableMapIterable.norm`

### `AbstractMutableMapIterable`

```norm
class AbstractMutableMapIterable<K, V> extends AbstractMapIterable<K, V> implements MutableMapIterable<K, V>, MapIterable<K, V>, RichIterable<V>
```

Type parameters:

- `K`
- `V`

#### `AbstractMutableMapIterable`

```norm
AbstractMutableMapIterable(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.multimap`

Source: `multimap/AbstractMultimap.norm`

### `AbstractMultimap`

```norm
class AbstractMultimap<K, V, C extends RichIterable<V>> implements Multimap<K, V>
```

Type parameters:

- `K`
- `V`
- `C` extends `RichIterable<V>`

#### `AbstractMultimap`

```norm
AbstractMultimap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.multimap`

Source: `multimap/AbstractMutableMultimap.norm`

### `AbstractMutableMultimap`

```norm
class AbstractMutableMultimap<K, V, C extends MutableCollection<V>> extends AbstractMultimap<K, V, C> implements MutableMultimap<K, V>, Multimap<K, V>
```

Type parameters:

- `K`
- `V`
- `C` extends `MutableCollection<V>`

#### `AbstractMutableMultimap`

```norm
AbstractMutableMultimap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.multimap.list`

Source: `multimap/list/AbstractMutableListMultimap.norm`

### `AbstractMutableListMultimap`

```norm
class AbstractMutableListMultimap<K, V> extends AbstractMutableMultimap<K, V, MutableList<V>> implements MutableListMultimap<K, V>, MutableMultimap<K, V>, Multimap<K, V>
```

Type parameters:

- `K`
- `V`

#### `AbstractMutableListMultimap`

```norm
AbstractMutableListMultimap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.org.eclipse.collections.api`

Source: `org/eclipse/collections/api/IntIterable.norm`

### `IntIterable`

```norm
interface IntIterable extends PrimitiveIterable
```

## `eclipse.collections.org.eclipse.collections.api`

Source: `org/eclipse/collections/api/InternalIterable.norm`

### `InternalIterable`

```norm
interface InternalIterable<T> extends Iterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api`

Source: `org/eclipse/collections/api/PrimitiveIterable.norm`

### `PrimitiveIterable`

```norm
interface PrimitiveIterable
```

## `eclipse.collections.org.eclipse.collections.api`

Source: `org/eclipse/collections/api/RichIterable.norm`

### `RichIterable`

```norm
interface RichIterable<T> extends InternalIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.collection`

Source: `org/eclipse/collections/api/collection/MutableCollection.norm`

### `MutableCollection`

```norm
interface MutableCollection<T> extends Collection<T>, RichIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.collection.primitive`

Source: `org/eclipse/collections/api/collection/primitive/MutableIntCollection.norm`

### `MutableIntCollection`

```norm
interface MutableIntCollection extends IntIterable
```

## `eclipse.collections.org.eclipse.collections.api.list`

Source: `org/eclipse/collections/api/list/ListIterable.norm`

### `ListIterable`

```norm
interface ListIterable<T> extends ReversibleIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.list`

Source: `org/eclipse/collections/api/list/MutableList.norm`

### `MutableList`

```norm
interface MutableList<T> extends MutableCollection<T>, JavaList<T>, Cloneable, ListIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.list.primitive`

Source: `org/eclipse/collections/api/list/primitive/IntList.norm`

### `IntList`

```norm
interface IntList extends ReversibleIntIterable
```

## `eclipse.collections.org.eclipse.collections.api.list.primitive`

Source: `org/eclipse/collections/api/list/primitive/MutableIntList.norm`

### `MutableIntList`

```norm
interface MutableIntList extends MutableIntCollection, IntList
```

## `eclipse.collections.org.eclipse.collections.api.map`

Source: `org/eclipse/collections/api/map/MapIterable.norm`

### `MapIterable`

```norm
interface MapIterable<K, V> extends RichIterable<V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.map`

Source: `org/eclipse/collections/api/map/MutableMap.norm`

### `MutableMap`

```norm
interface MutableMap<K, V> extends MutableMapIterable<K, V>, UnsortedMapIterable<K, V>, Cloneable
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.map`

Source: `org/eclipse/collections/api/map/MutableMapIterable.norm`

### `MutableMapIterable`

```norm
interface MutableMapIterable<K, V> extends MapIterable<K, V>, JavaMap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.map`

Source: `org/eclipse/collections/api/map/UnsortedMapIterable.norm`

### `UnsortedMapIterable`

```norm
interface UnsortedMapIterable<K, V> extends MapIterable<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.multimap`

Source: `org/eclipse/collections/api/multimap/Multimap.norm`

### `Multimap`

```norm
interface Multimap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.multimap`

Source: `org/eclipse/collections/api/multimap/MutableMultimap.norm`

### `MutableMultimap`

```norm
interface MutableMultimap<K, V> extends Multimap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.multimap.list`

Source: `org/eclipse/collections/api/multimap/list/ListMultimap.norm`

### `ListMultimap`

```norm
interface ListMultimap<K, V> extends ReversibleIterableMultimap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.multimap.list`

Source: `org/eclipse/collections/api/multimap/list/MutableListMultimap.norm`

### `MutableListMultimap`

```norm
interface MutableListMultimap<K, V> extends ListMultimap<K, V>, MutableMultimap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.multimap.ordered`

Source: `org/eclipse/collections/api/multimap/ordered/OrderedIterableMultimap.norm`

### `OrderedIterableMultimap`

```norm
interface OrderedIterableMultimap<K, V> extends Multimap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.multimap.ordered`

Source: `org/eclipse/collections/api/multimap/ordered/ReversibleIterableMultimap.norm`

### `ReversibleIterableMultimap`

```norm
interface ReversibleIterableMultimap<K, V> extends OrderedIterableMultimap<K, V>
```

Type parameters:

- `K`
- `V`

## `eclipse.collections.org.eclipse.collections.api.ordered`

Source: `org/eclipse/collections/api/ordered/OrderedIterable.norm`

### `OrderedIterable`

```norm
interface OrderedIterable<T> extends RichIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.ordered`

Source: `org/eclipse/collections/api/ordered/ReversibleIterable.norm`

### `ReversibleIterable`

```norm
interface ReversibleIterable<T> extends OrderedIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.ordered.primitive`

Source: `org/eclipse/collections/api/ordered/primitive/OrderedIntIterable.norm`

### `OrderedIntIterable`

```norm
interface OrderedIntIterable extends IntIterable
```

## `eclipse.collections.org.eclipse.collections.api.ordered.primitive`

Source: `org/eclipse/collections/api/ordered/primitive/ReversibleIntIterable.norm`

### `ReversibleIntIterable`

```norm
interface ReversibleIntIterable extends OrderedIntIterable
```

## `eclipse.collections.org.eclipse.collections.api.set`

Source: `org/eclipse/collections/api/set/MutableSet.norm`

### `MutableSet`

```norm
interface MutableSet<T> extends UnsortedSetIterable<T>, MutableSetIterable<T>, Cloneable
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.set`

Source: `org/eclipse/collections/api/set/MutableSetIterable.norm`

### `MutableSetIterable`

```norm
interface MutableSetIterable<T> extends SetIterable<T>, MutableCollection<T>, JavaSet<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.set`

Source: `org/eclipse/collections/api/set/Pool.norm`

### `Pool`

```norm
interface Pool<V>
```

Type parameters:

- `V`

## `eclipse.collections.org.eclipse.collections.api.set`

Source: `org/eclipse/collections/api/set/SetIterable.norm`

### `SetIterable`

```norm
interface SetIterable<T> extends RichIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.org.eclipse.collections.api.set`

Source: `org/eclipse/collections/api/set/UnsortedSetIterable.norm`

### `UnsortedSetIterable`

```norm
interface UnsortedSetIterable<T> extends SetIterable<T>
```

Type parameters:

- `T`

## `eclipse.collections.parallel`

Source: `parallel/BatchIterable.norm`

### `BatchIterable`

```norm
interface BatchIterable<E>
```

Type parameters:

- `E`

## `eclipse.collections.primitive`

Source: `primitive/AbstractIntIterable.norm`

### `AbstractIntIterable`

```norm
class AbstractIntIterable implements IntIterable
```

#### `AbstractIntIterable`

```norm
AbstractIntIterable(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `eclipse.collections.set`

Source: `set/AbstractUnifiedSet.norm`

### `AbstractUnifiedSet`

```norm
class AbstractUnifiedSet<T> extends AbstractMutableCollection<T> implements MutableSet<T>, Pool<T>, BatchIterable<T>, MutableCollection<T>, RichIterable<T>
```

Type parameters:

- `T`

#### `AbstractUnifiedSet`

```norm
AbstractUnifiedSet(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`
