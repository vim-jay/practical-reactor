# Flux Methods Reference

> ⚠️ = Deprecated

---

## Static Factory Methods

| Method | Method | Method |
|---|---|---|
| `combineLatest` | `firstWithSignal` | `mergeSequential` |
| `concat` | `firstWithValue` | `mergeSequentialDelayError` |
| `concatDelayError` | `from` | `never` |
| `create` | `fromArray` | `push` |
| `defer` | `fromIterable` | `range` |
| `deferContextual` | `fromStream` | `switchOnNext` |
| `deferWithContext` ⚠️ | `generate` | `using` |
| `empty` | `interval` | `usingWhen` |
| `error` | `just` | `zip` |
| `first` ⚠️ | `merge` | |
| `mergeComparing` | `mergeComparingDelayError` | `mergeDelayError` |
| `mergeOrdered` ⚠️ | | |

---

## Instance Methods

### Blocking
| Method | Method |
|---|---|
| `blockFirst` | `blockLast` |

### Buffering
| Method | Method | Method |
|---|---|---|
| `buffer` | `bufferTimeout` | `bufferUntil` |
| `bufferUntilChanged` | `bufferWhen` | `bufferWhile` |

### Caching & Replaying
| Method | Method |
|---|---|
| `cache` | `replay` |

### Collecting
| Method | Method | Method |
|---|---|---|
| `collect` | `collectList` | `collectMap` |
| `collectMultimap` | `collectSortedList` | |

### Combining
| Method | Method | Method |
|---|---|---|
| `concatWith` | `concatWithValues` | `groupJoin` |
| `join` | `mergeComparingWith` | `mergeWith` |
| `mergeOrderedWith` ⚠️ | `or` | `startWith` |
| `withLatestFrom` | `zipWith` | `zipWithIterable` |

### Context
| Method | Method |
|---|---|
| `contextWrite` | `subscriberContext` ⚠️ |

### Error Handling
| Method | Method | Method |
|---|---|---|
| `onErrorContinue` | `onErrorMap` | `onErrorResume` |
| `onErrorReturn` | `onErrorStop` | |

### Filtering
| Method | Method | Method |
|---|---|---|
| `distinct` | `distinctUntilChanged` | `elementAt` |
| `filter` | `filterWhen` | `ignoreElements` |
| `ofType` | `single` | `takeLast` |
| `takeUntil` | `takeUntilOther` | `takeWhile` |
| `skip` | `skipLast` | `skipUntil` |
| `skipUntilOther` | `skipWhile` | |

### FlatMapping
| Method | Method | Method |
|---|---|---|
| `concatMap` | `concatMapDelayError` | `concatMapIterable` |
| `flatMap` | `flatMapDelayError` | `flatMapIterable` |
| `flatMapSequential` | `flatMapSequentialDelayError` | `switchMap` |

### Lifecycle Hooks
| Method | Method | Method |
|---|---|---|
| `doAfterTerminate` | `doFinally` | `doFirst` |
| `doOnCancel` | `doOnComplete` | `doOnDiscard` |
| `doOnEach` | `doOnError` | `doOnNext` |
| `doOnRequest` | `doOnSubscribe` | `doOnTerminate` |

### Mapping & Transforming
| Method | Method | Method |
|---|---|---|
| `as` | `cast` | `dematerialize` |
| `expand` | `expandDeep` | `handle` |
| `index` | `map` | `mapNotNull` |
| `materialize` | `scan` | `scanWith` |
| `switchIfEmpty` | `switchOnFirst` | `transform` |
| `transformDeferred` | `transformDeferredContextual` | |

### Metrics & Debugging
| Method | Method | Method |
|---|---|---|
| `checkpoint` | `log` | `metrics` |
| `name` | `tag` | |

### Multicasting
| Method | Method | Method |
|---|---|---|
| `publish` | `publishNext` ⚠️ | `share` |
| `shareNext` | `parallel` | |

### Reducing
| Method | Method | Method |
|---|---|---|
| `all` | `any` | `count` |
| `hasElement` | `hasElements` | `reduce` |
| `reduceWith` | `sort` | |

### Repeating & Retrying
| Method | Method | Method |
|---|---|---|
| `repeat` | `repeatWhen` | `retry` |
| `retryWhen` | | |

### Sampling
| Method | Method | Method |
|---|---|---|
| `sample` | `sampleFirst` | `sampleTimeout` |

### Scheduling
| Method | Method | Method |
|---|---|---|
| `cancelOn` | `publishOn` | `subscribeOn` |

### Subscribing
| Method | Method | Method |
|---|---|---|
| `subscribe` | `subscribeWith` | |

### Taking
| Method | Method |
|---|---|
| `take` | `takeLast` |

### Terminal
| Method | Method | Method |
|---|---|---|
| `next` | `then` | `thenEmpty` |
| `thenMany` | `toIterable` | `toStream` |

### Time-related
| Method | Method | Method |
|---|---|---|
| `delayElements` | `delaySequence` | `delaySubscription` |
| `delayUntil` | `elapsed` | `timed` |
| `timeout` | `timestamp` | |

### Windowing
| Method | Method | Method |
|---|---|---|
| `window` | `windowTimeout` | `windowUntil` |
| `windowUntilChanged` | `windowWhen` | `windowWhile` |

### Backpressure
| Method | Method | Method |
|---|---|---|
| `onBackpressureBuffer` | `onBackpressureDrop` | `onBackpressureError` |
| `onBackpressureLatest` | `limitRate` | `limitRequest` ⚠️ |

### Miscellaneous
| Method | Method | Method |
|---|---|---|
| `defaultIfEmpty` | `groupBy` | `hide` |
| `getPrefetch` | `onTerminateDetach` | |
