# Fintech-VideoAd-script

面向金融App的Facebook信息流视频广告脚本技能，适配用户提供演员参考图后进行AI图生视频的制作流程。

## 能力与约定

- 五类脚本：口播、剧情、街头偶遇、采访、电话客服。
- 自动区分初步创意完善、已有文案完善、先提供创意方向三种需求。
- 绿背景口播素材适合后期抠像；与手机屏幕绿幕分别处理。
- 当前默认30秒以内，支持45秒以内、60秒以内；明确的更短时长优先。
- 产品参数按项目单独提供，不跨品牌复用旧数字。

## 文件

- `SKILL.md`：技能入口与工作规范。
- `agents/openai.yaml`：显示名称和简介。
- `references/script-types.md`：五类脚本方法与旧稿提炼。
- `references/library-lessons.md`：用户脚本集学习与时长方法。

## 使用

将技能文件保存到 Codex 个人技能目录的 `fintech-videoad-script` 文件夹，在支持技能的会话中使用 `$fintech-videoad-script`。

仓库保存可复用技能及提炼结果，不包含原始PDF、聊天导出、演员图片、视频或临时提取文件。

## 同步

本机技能修改后同步至此公开仓库，并每日检查遗漏；无变化不提交。具体范围与冲突处理见 references/github-sync.md。
