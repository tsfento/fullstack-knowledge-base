# Isolated vs Non-Isolated Tests
01. A pipe can be tested totally independent of angular
02. Basically, anything that doesn't rely on angular specific features can be tested isolated as a normal unit test
03. Created a ReversePipe to shared folder that reverses a string
04. Created a reverse.pip.spec.ts file
05. Copied code from user.component.spec.ts
06. Overkill, because deleted almost everything
07. Got rid of all imports and all but one it test block and the beforeEach
08. In clered it block, assigned reversePipe to new ReversePipe()
09. expect(reversePipe.transform('hello')).toEqual('olleh')
10. This is all that is needed since this pipe does not rely angular to function