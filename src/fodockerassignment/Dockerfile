FROM openjdk:11

# Set the working directory inside the container
WORKDIR /usr/src/myapp

# Copy the current directory contents into the container
COPY . /usr/src/myapp

# Create the package directory inside the container
RUN mkdir -p fodockerassignment

# Move the Java file to the package directory
RUN mv DemoClass.java fodockerassignment/

# Compile the Java program
RUN javac fodockerassignment/DemoClass.java

# Run the Java program using the fully qualified name
CMD ["java", "fodockerassignment.DemoClass"]   
