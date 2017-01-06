# RXjavaDoc
这是一篇Rxjava相关的翻译文档

aggregate( ) — see reduce( )

all( ) — determine whether all items emitted by an Observable meet some criteria
         确定可观察者排放的所有items是否满足某些标准。

amb( ) — given two or more source Observables, emits all of the items from the first of these Observables to emit an item
         给定两个或多个源可观察者,释放所有的item，从第一个可观察者发出一个item。

ambWith( ) — instance version of amb( )
             amb( )的实例版本。

and( ) — combine the emissions from two or more source Observables into a Pattern (rxjava-joins)
         结合两个或两个以上的排放源可观察者到一个模式(rxjava-joins)。

apply( ) (scala) — see create( )

asObservable( ) (kotlin) — see from( ) (et al.)

asyncAction( ) — convert an Action into an Observable that executes the Action and emits its return value (rxjava-async)
                 转换一个操作成为一个执行该操作的可观察者，并释放返回值(rxjava-async)。

asyncFunc( ) — convert a function into an Observable that executes the function and emits its return value (rxjava-async)
               转换一个方法成为一个执行该方法的可观察者，并释放返回值(rxjava-async)。

averageDouble( ) — calculates the average of Doubles emitted by an Observable and emits this average (rxjava-math)
                   计算由一个观察者发出的Doubles的平均值，并且释放这个平均值(rxjava-math)。

averageFloat( ) — calculates the average of Floats emitted by an Observable and emits this average (rxjava-math)
                  计算由一个观察者发出的Floats的平均值，并且释放这个平均值(rxjava-math)。

averageInteger( ) — calculates the average of Integers emitted by an Observable and emits this average (rxjava-math)
                    计算由一个观察者发出的Integers的平均值，并且释放这个平均值(rxjava-math)。

averageLong( ) — calculates the average of Longs emitted by an Observable and emits this average (rxjava-math)
                 计算由一个观察者发出的Longs的平均值，并且释放这个平均值(rxjava-math)。

blocking( ) (clojure) — see toBlocking( )

buffer( ) — periodically gather items from an Observable into bundles and emit these bundles rather than emitting the items one at a time
            定期从bundles里面某一个可观察者收集items,并且释放这些bundles而不是每次释放一个Item。

byLine( ) (StringObservable) — converts an Observable of Strings into an Observable of Lines by treating the source sequence as a stream and splitting it on line-endings
                               将一个字符串类型的可观察者转换成一个线性的可观察者，一个被当做流来序列化的并且在行的末尾快速的分离的可观察者。

cache( ) — remember the sequence of items emitted by the Observable and emit the same sequence to future Subscribers
           记住该观察者释放的items的序列，并且释放掉对未来用户发出的相同的序列。

cast( ) — cast all items from the source Observable into a particular type before reemitting them
          把所有来自源观察者的items映射到一个特定的类型，在重复释放它们之前。

catch( ) (clojure) — see onErrorResumeNext( )

chunkify( ) — returns an iterable that periodically returns a list of items emitted by the source Observable since the last list (⁇)
              返回一个iterable定期的被源可观察者返回的一个list of items 自从上一个list之后。

collect( ) — collects items emitted by the source Observable into a single mutable data structure and returns an Observable that emits this structure
             收集items，被源可观察者释放到一个单独的mutable data structure（一个可变的数据结构），并且返回一个释放该structure的可观察者。

