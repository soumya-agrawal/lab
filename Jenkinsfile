pipeline 
{
	 agent any 
	 
	 stages 
     {
		stage("compile") 
        {
			steps 
            {
				echo "Compiling"
				bat """ javac MyDate.java """
			}
		}
			
		stage ("run") 
        {
			steps 
            {
				echo "Running"
				bat """ java MyDate"""
			}
		}
			
	}
}
