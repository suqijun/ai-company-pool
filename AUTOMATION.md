# Weekly company-pool scan (Cursor Automation)

## Goal

Every Monday morning (Asia/Shanghai), discover **new or newly prominent** companies in these tracks and update this repo:

1. Coding / 研发 Agent
2. 办公效率 Agent
3. 客服销售 Agent
4. 电商运营 AI

## Must do

1. Read existing `20-信息/目标公司池.md` — never wipe prior rows; **append / update only**.
2. Search public sources (news, financing, product launches, careers keywords) for each track.
3. For each candidate, decide tier:
   - **A**: strong product + fit with B-side CRM / merchant / office narrative, worth deep apply
   - **B**: solid opportunity, normal apply
   - **C**: watchlist / practice / high-intensity caution
4. Append a dated「本周扫描纪要」section and update「变更日志」.
5. Keep `20-信息/目标公司池.html` in sync: update the `COMPANIES` array and scan-date text to match the Markdown.
6. Commit with message like: `chore(pool): weekly scan YYYY-MM-DD`.

## Head-signal rules

Promote into the pool if **any two** hold:

- Repeated mentions in track roundups / buyer guides
- Clear product name + public customer/scale signal
- Listed as cloud/collab ecosystem partner
- Stable AI PM / solution PM hiring

Soft PR only + no product roles → C or skip.

## Do not

- Invent jobs or salaries
- Remove companies without a one-line reason in the changelog
- Expand beyond the four priority tracks unless a company clearly spans them

## Search keywords

- Coding: `Coding Agent` `AI IDE` `Trae` `Qoder` `CodeBuddy` `研发效能`
- Office: `AI办公` `办公Agent` `WPS Comate` `千问办公` `飞书Aily`
- Sales/CS: `智能客服Agent` `销售Agent` `AI CRM` `智能外呼`
- E-com: `电商AI` `生意管家` `语流Agent` `AI店长`
