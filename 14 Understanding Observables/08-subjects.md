# Subjects
01. Subject is kind of a replacement for EventEmitter
02. Instead of emit(), you use next()
03. A subject is a special kind of observable
04. They are more "active" because you can actively trigger with next()
05. You still subscribe like an EventEmitter
06. Make sure you unsubscribe like other observables
07. You still want to use an EventEmitter with @Output
08. You only use subjects for cross component emitters