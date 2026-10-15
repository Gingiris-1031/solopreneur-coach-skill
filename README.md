# Solopreneur Coach

**An AI Skill for Starting a One-Person Business · by Gingiris**

[English](README.md) | [简体中文 · OPC Coach](README.zh-CN.md)

> Build your one-person business, one small step at a time.

Solopreneur Coach helps aspiring solopreneurs turn existing experience into a small experiment, validate a real need, and work toward a first paid client delivery. Start with your current situation. Get a useful draft. Try a manageable action. Bring back what happened and adjust.

**Status:** v0.1.0 public preview. English and Chinese instructions. Target-user testing and business outcomes are not yet validated; examples are fictional.

For Chinese-language discovery, **Gingiris OPC Coach** refers to this same skill. See the [Chinese introduction](https://tools.gingiris.com/zh/skills/opc-coach/).

## Who it is for

You have experience but are unsure what people would buy. You have an idea but little time to test it. Or someone has asked for help, and you need to define scope, price, and delivery.

Professional services are the deepest supported path. Product and content ideas are welcome for direction-setting and demand validation; this version does not claim complete operational coverage for every business model. You do not need to quit your job or register a company to explore an idea.

## Start with one message

After your agent has loaded the skill, say:

```text
Use gingiris-solopreneur-coach. I want to try building a one-person business,
but I don't know where to start. Ask me one easy question at a time,
and help me prepare one small action I can actually take.
```

Already have a specific problem? Try:

| Situation | Starter prompt |
| --- | --- |
| Experience, no offer | I've worked in design for five years. Help me identify one bounded service from work I've actually done. |
| Idea, little time | I want to build a resume tool and have two hours a week. Help me test the most important assumption first. |
| Interested client | Someone wants help with their content. Help me clarify what to deliver before I quote. |
| First job completed | My client is happy, but I spent too much time. Help me review what to change for the next project. |
| Stuck | I didn't do the last action. I have fifteen minutes today. Help me make the next step smaller. |

English and Chinese are supported in the instructions and stage references. The coach follows your language; ask to switch at any time. You can say “I don't know,” skip a question, correct an assumption, or request a direct draft.

## What your first conversation should produce

After one or two necessary clarifications, expect a provisional question to investigate, a small action matched to your constraints, and a usable asset such as an invitation, interview prompt, or service outline. The coach should explain what evidence to bring back and what might change the next decision.

A plan is a starting artifact. Real feedback comes from people and events outside the conversation.

## A short example

*Fictional teaching example; no income or outcome promise.*

**You:** I have five years of design experience and three hours a week. I don't know what to sell.

**Coach:** What was the most recent design problem someone asked you to help with?

**You:** A friend had a confusing restaurant menu. I helped organize it.

**Coach:** That suggests a small direction to test: making menu information easier to understand. We don't yet know whether other owners see this as worth paying for. Spend about twenty minutes preparing one before-and-after example you have permission to share. Here is a message you could choose to send to a relevant owner:

> I'm exploring common menu-design problems. Do customers repeatedly ask you to explain anything on your menu? If so, could you describe a recent example? There's no need to decide about a design service.

**You, later:** They have that problem but don't think it is worth paying for.

**Coach:** We learned that a problem exists, but payment interest hasn't appeared. Let's understand why before changing the offer, trying another customer situation, or setting this direction aside.

## Return with evidence

```text
Continue with gingiris-solopreneur-coach.
Last planned action:
What actually happened:
The person's words or actions, anonymized:
Time I have available now:
```

If nothing happened, say so. The next step may be smaller, clearer, delayed, or paused. If you start a new conversation, bring the previous progress summary. The skill does not guarantee cross-session memory or proactive reminders.

## Two kinds of progress

- **Learning loop:** question → action → external feedback → updated judgment → next decision. Deciding to stop an unsuitable direction can be useful progress.
- **Paid-business loop:** need → agreed scope and quote → agreed payment and start → delivery → acceptance → agreed payments settled → review. Remaining support obligations stay visible.

A free sample, a compliment, a deposit, and a completed paid job are different states. The coach keeps them separate.

## Install and start

With Node.js/npm available, run the Skills CLI in your chosen project:

```bash
npx skills add Gingiris-1031/solopreneur-coach-skill --skill gingiris-solopreneur-coach
```

Choose your agent and installation scope in the CLI. Installation downloads instructions; it does not launch a standalone app. In your agent, ask it to use `gingiris-solopreneur-coach`. Confirm it can read the entrypoint and a relevant reference. Host-specific automatic discovery can vary; model/service charges are separate.

For manual review, read [SKILL.md](skills/gingiris-solopreneur-coach/SKILL.md) and keep its `references/` directory with it. To uninstall, remove only this skill from the scope you selected using your host or Skills CLI management flow.

[GitHub source](https://github.com/Gingiris-1031/solopreneur-coach-skill) · [Hugging Face mirror](https://huggingface.co/datasets/Gingiris/solopreneur-coach-skill)

## What is inside

One bilingual entrypoint routes to only the relevant bilingual stage:

1. Starting point and small experiment.
2. Expertise and bounded offer.
3. Demand research and client fit.
4. Scope, pricing, and purchase state.
5. Delivery, acceptance, settlement, and review.

Core coaching needs no additional skills or private document access. When a concrete growth task arises, available [Gingiris skills](https://tools.gingiris.com/skills/) can optionally support it. Those tools are not bundled or automatically installed.

## Method and data

The workflow adapts Iris's professional experience and the supplied OPC/service-productization materials into coaching procedures. Personal accounts are not independent proof of business outcomes. See [method notes](METHOD.md).

Share only necessary information, preferably anonymized. Local skill files do not mean your prompts stay on your device; your AI host's data handling applies. Sending messages, publishing, or spending money requires relevant authorization.

Here, one-person business describes a way of working. “OPC” appears in some materials as One-Person Company; this skill is not a company-registration guide.

## Help improve it

Useful feedback: What were you stuck on? What did the coach produce? Did it help you take the next step? Remove private client details before sharing. Share anonymized feedback in [GitHub Issues](https://github.com/Gingiris-1031/solopreneur-coach-skill/issues).

## License / 许可证

[MIT](LICENSE) · Copyright 2026 Iris / Gingiris.

<!-- gingiris-community-cta:start -->
## 加入出海社群与购买资料包 · Community & Resources

- **加入出海社群：** 微信添加 **staywildgrow**，留言「**加入社群**」即可。
- **购买资料包：** 微信添加 **staywildgrow**，咨询购买 Gingiris 出海资料包，价格 **599 元人民币**。

- **Join the global growth community:** Add **staywildgrow** on WeChat and send **“加入社群”** (join the community).
- **Get the resource pack:** Add **staywildgrow** on WeChat to purchase the Gingiris global growth resource pack for **CNY 599**.

社群与资料包为可选入口，不影响本开源 Skill 的安装和使用。

The community and paid resource pack are optional; neither is required to install or use this open-source skill.
<!-- gingiris-community-cta:end -->
