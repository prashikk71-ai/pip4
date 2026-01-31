case "$ENVIRONMENT" in
  QA|UAT)
    cp target/pip4.war /home/prashik/Downloads/apache-tomcat-11.0.15/webapps
    echo "deployment has been done!"
    ;;
  *)
    echo "Unknown environment: $ENVIRONMENT"
    exit 1
    ;;
esac

