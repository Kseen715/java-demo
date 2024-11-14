BUILD_DIR = bin
SRC_DIR = src/main/java
SRC_FILES = $(wildcard $(SRC_DIR)/*.java)

build:
	mvn

jar: build
	jar -cmf manifest.mf $(BUILD_DIR)/HelloWorld.jar -C $(BUILD_DIR)/main/java .

run: jar
# java -cp $(BUILD_DIR) HelloWorld
	java -jar $(BUILD_DIR)/HelloWorld.jar