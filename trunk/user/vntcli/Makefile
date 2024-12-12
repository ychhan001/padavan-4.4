SRC_NAME = VNT-CLI
TARGET_FILE = vnt.sh
DEST_DIR = /usr/bin/

# 定义目标
all: install

# 拷贝文件的规则
install:
	@echo "Copying $(TARGET_FILE) to $(DEST_DIR)"
	@sudo cp $(TARGET_FILE) $(DEST_DIR)
	@sudo chmod +x $(DEST_DIR)$(TARGET_FILE)
	@echo "Installation complete."

# 清理（可选）
clean:
	@echo "No clean operation defined."
