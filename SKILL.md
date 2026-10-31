# caffeine.cache Skill

Use this skill to work with Norm module `caffeine.cache` version 4. Use only declarations listed below.

## `caffeine.cache`

Source: `Cache.norm`

### `Cache`

```norm
interface Cache<K, V>
```

Type parameters:

- `K`
- `V`

#### `asMap`

```norm
ConcurrentMap<K, V>? asMap()
```

Returns: `ConcurrentMap<K, V>?`

#### `cleanUp`

```norm
Void cleanUp()
```

Returns: `Void`

#### `estimatedSize`

```norm
Long estimatedSize()
```

Returns: `Long`

#### `get`

```norm
V? get(K? arg0, Function<V?(K?)>? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Function<V?(K?)>?`

Returns: `V?`

#### `getIfPresent`

```norm
V? getIfPresent(K? arg0)
```

Parameters:

- `arg0`: `K?`

Returns: `V?`

#### `invalidate`

```norm
Void invalidate(K? arg0)
```

Parameters:

- `arg0`: `K?`

Returns: `Void`

#### `put`

```norm
Void put(K? arg0, V? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`

Returns: `Void`

#### `stats`

```norm
CacheStats? stats()
```

Returns: `CacheStats?`

## `caffeine.cache`

Source: `CacheStats.norm`

### `CacheStats`

```norm
class CacheStats
```

#### `CacheStats`

```norm
CacheStats(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `averageLoadPenalty`

```norm
Double averageLoadPenalty()
```

Returns: `Double`

#### `evictionCount`

```norm
Long evictionCount()
```

Returns: `Long`

#### `evictionWeight`

```norm
Long evictionWeight()
```

Returns: `Long`

#### `hitCount`

```norm
Long hitCount()
```

Returns: `Long`

#### `hitRate`

```norm
Double hitRate()
```

Returns: `Double`

#### `loadCount`

```norm
Long loadCount()
```

Returns: `Long`

#### `loadFailureCount`

```norm
Long loadFailureCount()
```

Returns: `Long`

#### `loadFailureRate`

```norm
Double loadFailureRate()
```

Returns: `Double`

#### `loadSuccessCount`

```norm
Long loadSuccessCount()
```

Returns: `Long`

#### `minus`

```norm
CacheStats? minus(CacheStats? arg0)
```

Parameters:

- `arg0`: `CacheStats?`

Returns: `CacheStats?`

#### `missCount`

```norm
Long missCount()
```

Returns: `Long`

#### `missRate`

```norm
Double missRate()
```

Returns: `Double`

#### `plus`

```norm
CacheStats? plus(CacheStats? arg0)
```

Parameters:

- `arg0`: `CacheStats?`

Returns: `CacheStats?`

#### `requestCount`

```norm
Long requestCount()
```

Returns: `Long`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `totalLoadTime`

```norm
Long totalLoadTime()
```

Returns: `Long`

### `cacheStatsEmpty`

```norm
CacheStats? cacheStatsEmpty()
```

Returns: `CacheStats?`

## `caffeine.cache`

Source: `Caffeine.norm`

### `Caffeine`

```norm
class Caffeine<K, V>
```

Type parameters:

- `K`
- `V`

#### `Caffeine`

```norm
Caffeine(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `build`

```norm
Cache<K1, V1>? build<K1 extends K, V1 extends V>()
```

Type parameters:

- `K1` extends `K`
- `V1` extends `V`

Returns: `Cache<K1, V1>?`

#### `expireAfterAccess`

```norm
Caffeine<K, V>? expireAfterAccess(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `Caffeine<K, V>?`

#### `expireAfterWrite`

```norm
Caffeine<K, V>? expireAfterWrite(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `Caffeine<K, V>?`

#### `initialCapacity`

```norm
Caffeine<K, V>? initialCapacity(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Caffeine<K, V>?`

#### `maximumSize`

```norm
Caffeine<K, V>? maximumSize(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Caffeine<K, V>?`

#### `maximumWeight`

```norm
Caffeine<K, V>? maximumWeight(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Caffeine<K, V>?`

#### `recordStats`

```norm
Caffeine<K, V>? recordStats()
```

Returns: `Caffeine<K, V>?`

#### `refreshAfterWrite`

```norm
Caffeine<K, V>? refreshAfterWrite(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `Caffeine<K, V>?`

#### `softValues`

```norm
Caffeine<K, V>? softValues()
```

Returns: `Caffeine<K, V>?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `weakKeys`

```norm
Caffeine<K, V>? weakKeys()
```

Returns: `Caffeine<K, V>?`

#### `weakValues`

```norm
Caffeine<K, V>? weakValues()
```

Returns: `Caffeine<K, V>?`

### `caffeineFrom`

```norm
Caffeine<Any, Any>? caffeineFrom(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Caffeine<Any, Any>?`

### `caffeineNewBuilder`

```norm
Caffeine<Any, Any>? caffeineNewBuilder()
```

Returns: `Caffeine<Any, Any>?`

