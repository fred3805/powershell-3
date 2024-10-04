# powershell-3

PS C:\> Get-History

  Id CommandLine                                                                     
  -- -----------                                                                     
   1 Get-Host                                                                        
   2 Get-Host | Select-Object -Property Version                                      
   3 (Get-Host).GetType()                                                            
   4 (Get-Host | Select-Objet -Property Version).GetType()                           
   5 (Get-Host | Select-Object -Property Version).GetType()                          
   6 (Get-Host | Select-Object -Property Version).Version                            
   7 $ObjVersion = (Get-Host | Select-Object -Property Version).Version              
   8 $ObjVersion | Format-List -Property *                                           
   9 $ObjVersionMajor                                                                
  10 $ObjVersion | Format-List -Property *                                           
  11 C:\Users\fjoll\Documents\powershell 3.ps1                                       
  12 $ObjVersionMajor                                                                
  13 Start-Process calc.exe                                                          
  14 Start-Sleep -Seconds 1                                                          
  15 Start-Process calc.exe                                                          
  16 $AllProcess =Get-Process                                                        
  17 Set-Location c:\                                                                
  18 Get-ChildItem | Where Object {$_.Name -like "*program*"}                        
  19 Get-ChildItem | Where-Object {$_.Name -like "*program*"}                        
  20 Get-Process | Where-Object {$_.Name -like "*calc*"}                             
  21 $AllProcess | Where-Object {$_.Name -like "*calc*"}                             
