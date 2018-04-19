# NotifyPropertyEx-T-
This notify property class can make it easier for you to create NotifyProperty variables.

# Usage
  in c#:
  public NotifyPropertyEx<string> StudentID { get; } = string.Empty;
  how to set value?
    -> StudentID.Value = "Lisa";
    -> StudentID.SetValue("Lisa");
  
  in xaml:
  --tips: don't forget the "Value" in xaml binding.
  <TextBlock Text={Binding StudentID.Value} />
  
  that's all. enjoy it!
