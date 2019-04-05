# Code Convention

## Naming
| Identifier |	Casing	| Example |
| --- | --- | --- |
| Namespace |	Pascal |	namespace System.Security { ... } |
| Type |	Pascal |	public class StreamReader { ... } |
| Interface |	Pascal |	public interface IEnumerable { ... } |
| Method |	Pascal	| public class Object <br /> { <br /> &nbsp; &nbsp; public virtual string ToString(); <br /> } |
| Property |	Pascal |	public class String <br /> { <br /> &nbsp; &nbsp; public int Length { get; }  <br /> } |
| Event |	Pascal |	public class Process <br /> { <br /> &nbsp; &nbsp; public event EventHandler Exited; <br /> } |
| Field |	Pascal |	public class MessageQueue <br /> { <br /> &nbsp; &nbsp; public static readonly TimeSpan InfiniteTimeout; <br/>}<br/> public struct UInt32 { <br/>public const Min = 0; <br/> } |
| Enum value |	Pascal |	public enum FileMode {<br /> Append, <br />... <br />} |
| Parameter |	Camel |	public class Convert {<br /> public static int ToInt32(string value); <br/>} |

REF -> [Click!](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/capitalization-conventions)
