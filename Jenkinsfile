import com.rsg.jenkins.Cucumber

def utils = new Cucumber(steps)

node {
  cucumber(env.JOB_NAME, env.BUILD_NUMBER, env.BUILD_TAG) {
      echo "hello world"
  }
}
