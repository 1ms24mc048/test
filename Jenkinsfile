pipeline
{
	agent any
	stages
	{
		stage("Exec java file")
                {
                        steps {
                                        echo("Java file");
                                        sh "javac Hello.java"
										sh "java Hello"
                        }     
                }
		stage("Exec python file")
		{
			steps {
					echo("Python file");
					sh "python3 hello.py"
			}
		}
		
	}
}
