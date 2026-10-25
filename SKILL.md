# eclipse.collections Skill

Use this skill to work with Norm module `eclipse.collections` version 3. Use only declarations listed below.

## `eclipse.collections`

### `AbstractRichIterable`

```norm
class AbstractRichIterable<T> implements RichIterable<T>, Iterable<T?>
```

#### `AbstractRichIterable`

```norm
AbstractRichIterable(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections`

### `FastList`

```norm
class FastList<T> extends AbstractMutableList<T> implements BatchIterable<T>, JavaMutableList<T>, JavaMutableCollection<T>, RichIterable<T>, Iterable<T?>
```

#### `FastList`

```norm
FastList(__JarBindingToken token)
```

#### `add`

```norm
Void add(Integer arg0, T? arg1)
```

#### `add`

```norm
Boolean add(T? arg0)
```

#### `allSatisfy`

```norm
Boolean allSatisfy(Function<Boolean(T?)>? arg0)
```

#### `anySatisfy`

```norm
Boolean anySatisfy(Function<Boolean(T?)>? arg0)
```

#### `clear`

```norm
Void clear()
```

#### `collect`

```norm
FastList<V?>? collect<V>(Function<V?(T?)>? arg0)
```

#### `contains`

```norm
Boolean contains(Any? arg0)
```

#### `count`

```norm
Integer count(Function<Boolean(T?)>? arg0)
```

#### `get`

```norm
T? get(Integer arg0)
```

#### `getFirst`

```norm
T? getFirst()
```

#### `getLast`

```norm
T? getLast()
```

#### `groupBy`

```norm
FastListMultimap<V?, T?>? groupBy<V>(Function<V?(T?)>? arg0)
```

#### `isEmpty`

```norm
Boolean isEmpty()
```

#### `noneSatisfy`

```norm
Boolean noneSatisfy(Function<Boolean(T?)>? arg0)
```

#### `reject`

```norm
FastList<T?>? reject(Function<Boolean(T?)>? arg0)
```

#### `remove`

```norm
T? remove(Integer arg0)
```

#### `remove`

```norm
Boolean remove(Any? arg0)
```

#### `reverseThis`

```norm
FastList<T?>? reverseThis()
```

#### `select`

```norm
FastList<T?>? select(Function<Boolean(T?)>? arg0)
```

#### `size`

```norm
Integer size()
```

#### `sortThis`

```norm
FastList<T?>? sortThis()
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

### `fastListNew`

```norm
FastList<T?> fastListNew<T>()
```

## `eclipse.collections`

### `FastListMultimap`

```norm
class FastListMultimap<K, V> extends AbstractMutableListMultimap<K, V> implements MutableListMultimap<K, V>, MutableMultimap<K, V>, Multimap<K, V>
```

#### `FastListMultimap`

```norm
FastListMultimap(__JarBindingToken token)
```

#### `clear`

```norm
Void clear()
```

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

#### `containsKeyAndValue`

```norm
Boolean containsKeyAndValue(Any? arg0, Any? arg1)
```

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

#### `isEmpty`

```norm
Boolean isEmpty()
```

#### `notEmpty`

```norm
Boolean notEmpty()
```

#### `put`

```norm
Boolean put(K? arg0, V? arg1)
```

#### `remove`

```norm
Boolean remove(Any? arg0, Any? arg1)
```

#### `size`

```norm
Integer size()
```

#### `sizeDistinct`

```norm
Integer sizeDistinct()
```

### `fastListMultimapNew`

```norm
FastListMultimap<K?, V?> fastListMultimapNew<K, V>()
```

## `eclipse.collections`

### `IntArrayList`

```norm
class IntArrayList extends AbstractIntIterable implements MutableIntList, IntIterable
```

#### `IntArrayList`

```norm
IntArrayList(__JarBindingToken token)
```

#### `add`

```norm
Boolean add(Integer arg0)
```

#### `allSatisfy`

```norm
Boolean allSatisfy(Function<Boolean(Integer)>? arg0)
```

#### `anySatisfy`

```norm
Boolean anySatisfy(Function<Boolean(Integer)>? arg0)
```

#### `binarySearch`

```norm
Integer binarySearch(Integer arg0)
```

#### `contains`

```norm
Boolean contains(Integer arg0)
```

#### `count`

```norm
Integer count(Function<Boolean(Integer)>? arg0)
```

#### `get`

```norm
Integer get(Integer arg0)
```

#### `getFirst`

```norm
Integer getFirst()
```

#### `getLast`

```norm
Integer getLast()
```

#### `max`

```norm
Integer max()
```

#### `min`

```norm
Integer min()
```

#### `reject`

```norm
IntArrayList? reject(Function<Boolean(Integer)>? arg0)
```

#### `reverseThis`

```norm
IntArrayList? reverseThis()
```

#### `select`

```norm
IntArrayList? select(Function<Boolean(Integer)>? arg0)
```

#### `size`

```norm
Integer size()
```

#### `sortThis`

```norm
IntArrayList? sortThis()
```

#### `sum`

```norm
Long sum()
```

### `intArrayListNew`

```norm
IntArrayList intArrayListNew()
```

## `eclipse.collections`

### `UnifiedMap`

```norm
class UnifiedMap<K, V> extends AbstractMutableMap<K, V> implements BatchIterable<V>, JavaMutableMap<K, V>, MutableMapIterable<K, V>, MapIterable<K, V>, RichIterable<V>, Iterable<V?>
```

#### `UnifiedMap`

```norm
UnifiedMap(__JarBindingToken token)
```

#### `clear`

```norm
Void clear()
```

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

#### `get`

```norm
V? get(Any? arg0)
```

#### `getIfAbsentPut`

```norm
V? getIfAbsentPut(K? arg0, V? arg1)
```

#### `getIfAbsentPut`

```norm
V? getIfAbsentPut(K? arg0, Function<V?()>? arg1)
```

#### `isEmpty`

```norm
Boolean isEmpty()
```

#### `keySet`

```norm
MutableSet<K?>? keySet()
```

#### `put`

```norm
V? put(K? arg0, V? arg1)
```

#### `removeKey`

```norm
V? removeKey(K? arg0)
```

#### `size`

```norm
Integer size()
```

#### `values`

```norm
MutableCollection<V?>? values()
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

### `unifiedMapNew`

```norm
UnifiedMap<K?, V?> unifiedMapNew<K, V>()
```

## `eclipse.collections`

### `UnifiedSet`

```norm
class UnifiedSet<T> extends AbstractUnifiedSet<T> implements JavaMutableSet<T>, Pool<T>, BatchIterable<T>, JavaMutableCollection<T>, RichIterable<T>, Iterable<T?>
```

#### `UnifiedSet`

```norm
UnifiedSet(__JarBindingToken token)
```

#### `add`

```norm
Boolean add(T? arg0)
```

#### `clear`

```norm
Void clear()
```

#### `contains`

```norm
Boolean contains(Any? arg0)
```

#### `isEmpty`

```norm
Boolean isEmpty()
```

#### `remove`

```norm
Boolean remove(Any? arg0)
```

#### `size`

```norm
Integer size()
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

### `unifiedSetNew`

```norm
UnifiedSet<T?> unifiedSetNew<T>()
```

## `eclipse.collections.collection.mutable`

### `AbstractMutableCollection`

```norm
class AbstractMutableCollection<T> extends AbstractRichIterable<T> implements JavaMutableCollection<T>, RichIterable<T>, Iterable<T?>
```

#### `AbstractMutableCollection`

```norm
AbstractMutableCollection(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.list.mutable`

### `AbstractMutableList`

```norm
class AbstractMutableList<T> extends AbstractMutableCollection<T> implements JavaMutableList<T>, JavaMutableCollection<T>, RichIterable<T>, Iterable<T?>
```

#### `AbstractMutableList`

```norm
AbstractMutableList(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.map`

### `AbstractMapIterable`

```norm
class AbstractMapIterable<K, V> extends AbstractRichIterable<V> implements MapIterable<K, V>, RichIterable<V>, Iterable<V?>
```

#### `AbstractMapIterable`

```norm
AbstractMapIterable(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.map.mutable`

### `AbstractMutableMap`

```norm
class AbstractMutableMap<K, V> extends AbstractMutableMapIterable<K, V> implements JavaMutableMap<K, V>, MutableMapIterable<K, V>, MapIterable<K, V>, RichIterable<V>, Iterable<V?>
```

#### `AbstractMutableMap`

```norm
AbstractMutableMap(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.map.mutable`

### `AbstractMutableMapIterable`

```norm
class AbstractMutableMapIterable<K, V> extends AbstractMapIterable<K, V> implements MutableMapIterable<K, V>, MapIterable<K, V>, RichIterable<V>, Iterable<V?>
```

#### `AbstractMutableMapIterable`

```norm
AbstractMutableMapIterable(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.multimap`

### `AbstractMultimap`

```norm
class AbstractMultimap<K, V, C extends RichIterable<V>> implements Multimap<K, V>
```

#### `AbstractMultimap`

```norm
AbstractMultimap(__JarBindingToken token)
```

## `eclipse.collections.multimap`

### `AbstractMutableMultimap`

```norm
class AbstractMutableMultimap<K, V, C extends JavaMutableCollection<V>> extends AbstractMultimap<K, V, C> implements MutableMultimap<K, V>, Multimap<K, V>
```

#### `AbstractMutableMultimap`

```norm
AbstractMutableMultimap(__JarBindingToken token)
```

## `eclipse.collections.multimap.list`

### `AbstractMutableListMultimap`

```norm
class AbstractMutableListMultimap<K, V> extends AbstractMutableMultimap<K, V, JavaMutableList<V>> implements MutableListMultimap<K, V>, MutableMultimap<K, V>, Multimap<K, V>
```

#### `AbstractMutableListMultimap`

```norm
AbstractMutableListMultimap(__JarBindingToken token)
```

## `eclipse.collections.org.eclipse.collections.api`

### `IntIterable`

```norm
interface IntIterable extends PrimitiveIterable
```

## `eclipse.collections.org.eclipse.collections.api`

### `InternalIterable`

```norm
interface InternalIterable<T> extends Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api`

### `PrimitiveIterable`

```norm
interface PrimitiveIterable
```

## `eclipse.collections.org.eclipse.collections.api`

### `RichIterable`

```norm
interface RichIterable<T> extends InternalIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.collection`

### `JavaMutableCollection`

```norm
interface JavaMutableCollection<T> extends RichIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.collection.primitive`

### `MutableIntCollection`

```norm
interface MutableIntCollection extends IntIterable
```

## `eclipse.collections.org.eclipse.collections.api.list`

### `JavaMutableList`

```norm
interface JavaMutableList<T> extends JavaMutableCollection<T>, ListIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.list`

### `ListIterable`

```norm
interface ListIterable<T> extends ReversibleIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.list.primitive`

### `IntList`

```norm
interface IntList extends ReversibleIntIterable
```

## `eclipse.collections.org.eclipse.collections.api.list.primitive`

### `MutableIntList`

```norm
interface MutableIntList extends MutableIntCollection, IntList
```

## `eclipse.collections.org.eclipse.collections.api.map`

### `JavaMutableMap`

```norm
interface JavaMutableMap<K, V> extends MutableMapIterable<K, V>, UnsortedMapIterable<K, V>, Iterable<V?>
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.map`

### `MapIterable`

```norm
interface MapIterable<K, V> extends RichIterable<V>, Iterable<V?>
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.map`

### `MutableMapIterable`

```norm
interface MutableMapIterable<K, V> extends MapIterable<K, V>, Iterable<V?>
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.map`

### `UnsortedMapIterable`

```norm
interface UnsortedMapIterable<K, V> extends MapIterable<K, V>, Iterable<V?>
```

#### `iterator`

```norm
Iterator<V?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.multimap`

### `Multimap`

```norm
interface Multimap<K, V>
```

## `eclipse.collections.org.eclipse.collections.api.multimap`

### `MutableMultimap`

```norm
interface MutableMultimap<K, V> extends Multimap<K, V>
```

## `eclipse.collections.org.eclipse.collections.api.multimap.list`

### `ListMultimap`

```norm
interface ListMultimap<K, V> extends ReversibleIterableMultimap<K, V>
```

## `eclipse.collections.org.eclipse.collections.api.multimap.list`

### `MutableListMultimap`

```norm
interface MutableListMultimap<K, V> extends ListMultimap<K, V>, MutableMultimap<K, V>
```

## `eclipse.collections.org.eclipse.collections.api.multimap.ordered`

### `OrderedIterableMultimap`

```norm
interface OrderedIterableMultimap<K, V> extends Multimap<K, V>
```

## `eclipse.collections.org.eclipse.collections.api.multimap.ordered`

### `ReversibleIterableMultimap`

```norm
interface ReversibleIterableMultimap<K, V> extends OrderedIterableMultimap<K, V>
```

## `eclipse.collections.org.eclipse.collections.api.ordered`

### `OrderedIterable`

```norm
interface OrderedIterable<T> extends RichIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.ordered`

### `ReversibleIterable`

```norm
interface ReversibleIterable<T> extends OrderedIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.ordered.primitive`

### `OrderedIntIterable`

```norm
interface OrderedIntIterable extends IntIterable
```

## `eclipse.collections.org.eclipse.collections.api.ordered.primitive`

### `ReversibleIntIterable`

```norm
interface ReversibleIntIterable extends OrderedIntIterable
```

## `eclipse.collections.org.eclipse.collections.api.set`

### `JavaMutableSet`

```norm
interface JavaMutableSet<T> extends UnsortedSetIterable<T>, MutableSetIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.set`

### `MutableSetIterable`

```norm
interface MutableSetIterable<T> extends SetIterable<T>, JavaMutableCollection<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.set`

### `Pool`

```norm
interface Pool<V>
```

## `eclipse.collections.org.eclipse.collections.api.set`

### `SetIterable`

```norm
interface SetIterable<T> extends RichIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.org.eclipse.collections.api.set`

### `UnsortedSetIterable`

```norm
interface UnsortedSetIterable<T> extends SetIterable<T>, Iterable<T?>
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

## `eclipse.collections.parallel`

### `BatchIterable`

```norm
interface BatchIterable<E>
```

## `eclipse.collections.primitive`

### `AbstractIntIterable`

```norm
class AbstractIntIterable implements IntIterable
```

#### `AbstractIntIterable`

```norm
AbstractIntIterable(__JarBindingToken token)
```

## `eclipse.collections.set`

### `AbstractUnifiedSet`

```norm
class AbstractUnifiedSet<T> extends AbstractMutableCollection<T> implements JavaMutableSet<T>, Pool<T>, BatchIterable<T>, JavaMutableCollection<T>, RichIterable<T>, Iterable<T?>
```

#### `AbstractUnifiedSet`

```norm
AbstractUnifiedSet(__JarBindingToken token)
```

#### `iterator`

```norm
Iterator<T?> iterator()
```

