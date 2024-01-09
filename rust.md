```log
error[E0507]: cannot move out of `receiver`, a captured variable in an `Fn` closure
   --> src/lib.rs:109:34
    |
105 |     let (sender, receiver) = iced_mpsc::channel(1000);
    |                  -------- captured outer variable
...
109 |         Box::new(move || connect(receiver, args.uri.parse::<Endpoint>().unwrap())),
    |                  -------         ^^^^^^^^ move occurs because `receiver` has type `iced_futures::futures::futures_channel::mpsc::Receiver<ToServer>`, which does not implement the `Copy` trait
    |                  |
    |                  captured by this `Fn` closure
```