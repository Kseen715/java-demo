BUILD_DIR = build
SRC_DIR = src
SRC_FILES = $(wildcard $(SRC_DIR)/*.java)

build:
	javac -target 1.8 -source 1.8 $(SRC_FILES) -d $(BUILD_DIR)

jar: build
	jar -cmf manifest.mf $(BUILD_DIR)/HelloWorld.jar -C $(BUILD_DIR) .

run: jar
# java -cp $(BUILD_DIR) HelloWorld
	java -jar $(BUILD_DIR)/HelloWorld.jar