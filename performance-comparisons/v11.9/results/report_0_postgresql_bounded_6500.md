### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Save | avg | 10ms | 13ms | 3ms | 29.25
| StatusStore.SaveOrUpdateMany | avg | 8ms | 10ms | 2ms | 25.69
| ProductNoticesStore.ClearOldNotices | avg | 18ms | 22ms | 4ms | 22.63
| ChannelStore.AutocompleteInTeamForSearch | avg | 34ms | 39ms | 5ms | 14.51
| PostStore.SearchPostsForUser | avg | 116ms | 123ms | 7ms | 6.01
| PostStore.AnalyticsPostCount | avg | 130ms | 134ms | 4ms | 3.07
| UserStore.GetAllProfilesInChannel | avg | 143ms | 147ms | 4ms | 2.79
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetTotalMemberCount | p99 | 50ms | 237ms | 187ms | 375.88
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 22ms | 17ms | 343.43
| JobStore.UpdateStatusOptimistically | p99 | 5ms | 21ms | 16ms | 323.23
| StatusStore.SaveOrUpdateMany | p99 | 25ms | 90ms | 65ms | 260.29
| ScheduledPostStore.CreateScheduledPost | p99 | 9ms | 23ms | 14ms | 153.85
| PostStore.GetPostReminderMetadata | p99 | 5ms | 10ms | 5ms | 100.97
| FileInfoStore.GetForPost | p99 | 7ms | 10ms | 3ms | 42.50
| JobStore.UpdateOptimistically | p99 | 5ms | 7ms | 2ms | 40.40
| ReactionStore.GetForPost | p99 | 5ms | 7ms | 2ms | 40.15
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 12ms | 15ms | 3ms | 24.94
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 68ms | 83ms | 15ms | 22.22
| StatusStore.SaveOrUpdate | p99 | 19ms | 23ms | 4ms | 21.44
| ChannelStore.Get | p99 | 11ms | 13ms | 2ms | 17.41
| ThreadStore.GetTotalUnreadThreads | p99 | 12ms | 14ms | 2ms | 16.29
| SessionStore.GetLRUSessions | p99 | 15ms | 17ms | 2ms | 13.57
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 15ms | 17ms | 2ms | 13.17
| UserTermsOfServiceStore.GetByUser | p99 | 16ms | 18ms | 2ms | 12.56
| TeamStore.GetAllPage | p99 | 16ms | 18ms | 2ms | 12.21
| TeamStore.GetTeamsByUserId | p99 | 17ms | 19ms | 2ms | 11.86
| GroupStore.GetByName | p99 | 18ms | 20ms | 2ms | 11.08
| ChannelStore.GetChannelsByUser | p99 | 19ms | 21ms | 2ms | 10.33
| FileInfoStore.SetContent | p99 | 20ms | 22ms | 2ms | 10.22
| ChannelStore.GetGuestCount | p99 | 20ms | 22ms | 2ms | 9.76
| ChannelStore.GetMemberForPost | p99 | 35ms | 38ms | 3ms | 8.66
| PreferenceStore.Save | p99 | 49ms | 53ms | 4ms | 8.09
| UserStore.Count | p99 | 40ms | 42ms | 2ms | 4.97
| ChannelStore.Save | p99 | 42ms | 44ms | 2ms | 4.80
| TeamStore.SaveMember | p99 | 76ms | 79ms | 3ms | 3.94
| ProductNoticesStore.View | p99 | 188ms | 192ms | 4ms | 2.13
| UserStore.GetAllProfilesInChannel | p99 | 466ms | 471ms | 5ms | 1.07
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 2ms | 0s | -2ms | -121.27
| ThreadStore.MarkAllAsReadByTeam | avg | 5ms | 0s | -5ms | -107.51
| PostPersistentNotificationStore.UpdateLastActivity | avg | 4ms | 0s | -4ms | -99.95
| ChannelStore.CreateSidebarCategory | avg | 21ms | 0s | -21ms | -99.80
| PostStore.GetPostReminders | avg | 5ms | 3ms | -2ms | -37.92
| ChannelStore.GetPublicChannelsForTeam | avg | 14ms | 12ms | -2ms | -14.33
| ChannelStore.UpdateSidebarCategories | avg | 45ms | 40ms | -5ms | -11.04
| PostStore.Delete | avg | 18ms | 16ms | -2ms | -11.01
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| JobStore.GetAllByTypePage | p99 | 41ms | 5ms | -36ms | -87.80
| ChannelStore.AutocompleteInTeamForSearch | p99 | 645ms | 99ms | -546ms | -84.67
| StatusStore.UpdateExpiredDNDStatuses | p99 | 28ms | 6ms | -22ms | -80.00
| ChannelStore.UpdateSidebarCategories | p99 | 218ms | 50ms | -168ms | -76.89
| PostStore.GetPostReminders | p99 | 22ms | 9ms | -13ms | -57.91
| JobStore.GetCountByStatusAndType | p99 | 15ms | 7ms | -8ms | -53.51
| ChannelStore.Autocomplete | p99 | 213ms | 99ms | -114ms | -53.46
| PostStore.Delete | p99 | 48ms | 25ms | -23ms | -48.17
| JobStore.Save | p99 | 9ms | 5ms | -4ms | -43.80
| ClusterDiscoveryStore.SetLastPingAt | p99 | 16ms | 9ms | -7ms | -43.75
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.48
| SessionStore.Save | p99 | 31ms | 25ms | -6ms | -19.43
| StatusStore.Get | p99 | 13ms | 11ms | -2ms | -15.83
| UserStore.GetForLogin | p99 | 19ms | 17ms | -2ms | -10.72
| ChannelStore.CreateInitialSidebarCategories | p99 | 72ms | 66ms | -6ms | -8.33
| PostStore.Update | p99 | 27ms | 25ms | -2ms | -7.34
| UserStore.AutocompleteUsersInChannel | p99 | 166ms | 161ms | -5ms | -3.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 1ms | 3ms | 2ms | 178.92
| getTeamStats | avg | 34ms | 45ms | 11ms | 32.12
| createChannelBookmark | avg | 16ms | 20ms | 4ms | 24.26
| logout | avg | 23ms | 26ms | 3ms | 12.88
| autocompleteChannelsForTeamForSearch | avg | 35ms | 39ms | 4ms | 11.59
| createDirectChannel | avg | 152ms | 166ms | 14ms | 9.22
| searchPostsInTeam | avg | 121ms | 129ms | 8ms | 6.63
| createGroupChannel | avg | 244ms | 254ms | 10ms | 4.10
| createChannel | avg | 178ms | 183ms | 5ms | 2.81
| createPost | avg | 145ms | 149ms | 4ms | 2.76
| addChannelMember | avg | 151ms | 155ms | 4ms | 2.65
| addTeamMember | avg | 594ms | 608ms | 14ms | 2.36
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamStats | p99 | 50ms | 237ms | 187ms | 375.88
| unfollowThreadByUser | p99 | 25ms | 78ms | 53ms | 213.28
| createSchedulePost | p99 | 10ms | 23ms | 13ms | 132.31
| setPostReminder | p99 | 25ms | 48ms | 23ms | 92.52
| upsertDraft | p99 | 11ms | 13ms | 2ms | 18.03
| getFileThumbnail | p99 | 114ms | 133ms | 19ms | 16.61
| createPost | p99 | 562ms | 645ms | 83ms | 14.78
| createDirectChannel | p99 | 248ms | 280ms | 32ms | 12.88
| getTeamsForUser | p99 | 17ms | 19ms | 2ms | 11.65
| getAllTeams | p99 | 19ms | 21ms | 2ms | 10.40
| getFilePreview | p99 | 148ms | 162ms | 14ms | 9.49
| viewChannel | p99 | 25ms | 27ms | 2ms | 8.01
| getPostsForChannelAroundLastUnread | p99 | 67ms | 71ms | 4ms | 5.93
| addTeamMember | p99 | 1.97s | 2.078s | 108ms | 5.48
| getChannelMember | p99 | 37ms | 39ms | 2ms | 5.40
| getPostsForChannel | p99 | 92ms | 96ms | 4ms | 4.34
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 5ms | 0s | -5ms | -105.86
| getFilteredUsersStats | avg | 9ms | 0s | -9ms | -103.18
| getUsersByGroupChannelIds | avg | 3ms | 0s | -3ms | -102.05
| getChannelMembers | avg | 2ms | 0s | -2ms | -101.77
| handleCheckCWSConnection | avg | 59ms | 0s | -59ms | -100.69
| getAnalytics | avg | 39ms | 0s | -39ms | -99.97
| createCategoryForTeamForUser | avg | 22ms | 0s | -22ms | -99.60
| getPublicChannelsForTeam | avg | 15ms | 13ms | -2ms | -13.55
| login | avg | 97ms | 85ms | -12ms | -12.39
| updateCategoriesForTeamForUser | avg | 58ms | 51ms | -7ms | -12.04
| removeUserCustomStatus | avg | 102ms | 99ms | -3ms | -2.93
| getProfileImage | avg | 106ms | 103ms | -3ms | -2.84
| uploadFileStream | avg | 460ms | 455ms | -5ms | -1.09
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| getFilteredUsersStats | p99 | 10ms | 0s | -10ms | -100.50
| getAnalytics | p99 | 50ms | 0s | -50ms | -100.50
| handleCheckCWSConnection | p99 | 99ms | 0s | -99ms | -99.75
| getJobsByType | p99 | 41ms | 5ms | -36ms | -87.80
| autocompleteChannelsForTeamForSearch | p99 | 645ms | 99ms | -546ms | -84.67
| updateCategoriesForTeamForUser | p99 | 218ms | 99ms | -119ms | -54.46
| searchAllChannels | p99 | 213ms | 99ms | -114ms | -53.46
| deletePost | p99 | 48ms | 25ms | -23ms | -48.17
| login | p99 | 474ms | 250ms | -224ms | -47.21
| root | p99 | 9ms | 5ms | -4ms | -42.44
| listCPAFields | p99 | 29ms | 24ms | -5ms | -17.13
| patchPost | p99 | 56ms | 49ms | -7ms | -12.61
| autocompleteUsers | p99 | 137ms | 132ms | -5ms | -3.64
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.487
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.478
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 10ms| 13ms | 3ms | 29.246
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 5ms | 1ms | 22.788
| |  P99| 20ms| 21ms | 1ms | 5.010
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 35ms| 34ms | -1ms | -2.872
| |  P99| 213ms| 99ms | -114ms | -53.457
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 34ms| 39ms | 5ms | 14.512
| |  P99| 645ms| 99ms | -546ms | -84.667
| ChannelStore.CreateDirectChannel |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 50ms| 51ms | 1ms | 2.019
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 72ms| 66ms | -6ms | -8.331
| ChannelStore.CreateSidebarCategory |  Avg| 21ms| 0s | -21ms | -99.799
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 17.411
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.579
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 12ms | 1ms | 9.051
| |  P99| 68ms| 83ms | 15ms | 22.222
| ChannelStore.GetBoardChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.142
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 0s | -1ms | -97.023
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.329
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.760
| ChannelStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.928
| ChannelStore.GetMemberCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.323
| ChannelStore.GetMemberForPost |  Avg| 21ms| 20ms | -1ms | -4.862
| |  P99| 35ms| 38ms | 3ms | 8.662
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.626
| ChannelStore.GetMembers |  Avg| 2ms| 0s | -2ms | -121.268
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 14ms| 12ms | -2ms | -14.332
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.343
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 5ms | -1ms | -17.123
| |  P99| 24ms| 23ms | -1ms | -4.255
| ChannelStore.GetTeamChannels |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 12ms | 1ms | 8.748
| |  P99| 42ms| 44ms | 2ms | 4.805
| ChannelStore.SaveMember |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 95ms| 96ms | 1ms | 1.051
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.142
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 45ms| 40ms | -5ms | -11.042
| |  P99| 218ms| 50ms | -168ms | -76.888
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -43.750
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 5ms | 1ms | 26.273
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 2ms | 1ms | 66.687
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.714
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 42.504
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -6.909
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.756
| |  P99| 20ms| 22ms | 2ms | 10.224
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.517
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.076
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.058
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 0s | -1ms | -68.882
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.636
| JobStore.GetAllByTypePage |  Avg| 2ms| 1ms | -1ms | -49.176
| |  P99| 41ms| 5ms | -36ms | -87.798
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 7ms | -8ms | -53.512
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.796
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 5ms | 1ms | 22.826
| |  P99| 5ms| 21ms | 16ms | 323.232
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 3ms | 1ms | 40.871
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 0s | -4ms | -99.950
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPostWithContext |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 130ms| 134ms | 4ms | 3.071
| |  P99| 495ms| 495ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 18ms| 16ms | -2ms | -11.012
| |  P99| 48ms| 25ms | -23ms | -48.167
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.772
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.974
| PostStore.GetPostReminders |  Avg| 5ms| 3ms | -2ms | -37.923
| |  P99| 22ms| 9ms | -13ms | -57.906
| PostStore.GetPosts |  Avg| 2ms| 3ms | 1ms | 40.296
| |  P99| 17ms| 18ms | 1ms | 5.820
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.152
| PostStore.GetPostsByIds |  Avg| 1ms| 0s | -1ms | -83.943
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.063
| PostStore.SearchPostsForUser |  Avg| 116ms| 123ms | 7ms | 6.014
| |  P99| 966ms| 969ms | 3ms | 0.311
| PostStore.SetPostReminder |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 27ms| 25ms | -2ms | -7.340
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.844
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 12ms| 13ms | 1ms | 8.063
| |  P99| 49ms| 53ms | 4ms | 8.093
| ProductNoticesStore.ClearOldNotices |  Avg| 18ms| 22ms | 4ms | 22.634
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 45ms| 46ms | 1ms | 2.199
| |  P99| 188ms| 192ms | 4ms | 2.131
| PropertyFieldStore.SearchPropertyFields |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.620
| PropertyGroupStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| PropertyValueStore.SearchPropertyValues |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.150
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -113.892
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 5ms | 1ms | 23.583
| |  P99| 9ms| 23ms | 14ms | 153.846
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 2ms | 1ms | 109.748
| |  P99| 5ms| 22ms | 17ms | 343.434
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.939
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 2ms | -1ms | -39.192
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 1ms | -1ms | -66.426
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 35ms | 1ms | 2.923
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.575
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.549
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 31ms| 25ms | -6ms | -19.425
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.830
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 5ms | 1ms | 22.318
| |  P99| 19ms| 23ms | 4ms | 21.439
| StatusStore.SaveOrUpdateMany |  Avg| 8ms| 10ms | 2ms | 25.687
| |  P99| 25ms| 90ms | 65ms | 260.292
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 6ms | -22ms | -80.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.798
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 0s | -1ms | -123.614
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 2ms | 1ms | 79.265
| |  P99| 16ms| 18ms | 2ms | 12.206
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.171
| TeamStore.GetMany |  Avg| 1ms| 0s | -1ms | -137.035
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.654
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 2ms | 1ms | 71.112
| |  P99| 17ms| 19ms | 2ms | 11.855
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 33ms| 32ms | -1ms | -3.019
| |  P99| 50ms| 237ms | 187ms | 375.879
| TeamStore.SaveMember |  Avg| 25ms| 26ms | 1ms | 3.929
| |  P99| 76ms| 79ms | 3ms | 3.944
| TemporaryPostStore.GetExpiredPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.774
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.860
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.525
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.453
| ThreadStore.GetTotalThreads |  Avg| 1ms| 2ms | 1ms | 72.067
| |  P99| 13ms| 14ms | 1ms | 7.566
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 9.424
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 2ms | 1ms | 71.688
| |  P99| 12ms| 14ms | 2ms | 16.291
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.358
| ThreadStore.MaintainMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 4ms | 1ms | 30.749
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 5ms| 0s | -5ms | -107.507
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 3ms| 2ms | -1ms | -39.614
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 166ms| 161ms | -5ms | -3.008
| UserStore.Count |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 4.967
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.996
| UserStore.GetAllProfilesInChannel |  Avg| 143ms| 147ms | 4ms | 2.789
| |  P99| 466ms| 471ms | 5ms | 1.074
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.718
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.122
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.347
| UserStore.Save |  Avg| 117ms| 117ms | 0s | 0.000
| |  P99| 248ms| 249ms | 1ms | 0.403
| UserStore.Search |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.Update |  Avg| 8ms| 9ms | 1ms | 12.123
| |  P99| 22ms| 23ms | 1ms | 4.640
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.510
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.562
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 3ms | 1ms | 41.003
| |  P99| 15ms| 14ms | -1ms | -6.767
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 151ms| 155ms | 4ms | 2.647
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 594ms| 608ms | 14ms | 2.356
| | P99| 1.97s| 2.078s | 108ms | 5.482
| autocompleteChannelsForTeamForSearch | Avg| 35ms| 39ms | 4ms | 11.587
| | P99| 645ms| 99ms | -546ms | -84.667
| autocompleteUsers | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 137ms| 132ms | -5ms | -3.639
| createCategoryForTeamForUser | Avg| 22ms| 0s | -22ms | -99.604
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 178ms| 183ms | 5ms | 2.812
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 16ms| 20ms | 4ms | 24.260
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 152ms| 166ms | 14ms | 9.215
| | P99| 248ms| 280ms | 32ms | 12.885
| createGroupChannel | Avg| 244ms| 254ms | 10ms | 4.104
| | P99| 495ms| 496ms | 1ms | 0.202
| createPost | Avg| 145ms| 149ms | 4ms | 2.755
| | P99| 562ms| 645ms | 83ms | 14.781
| createSchedulePost | Avg| 5ms| 6ms | 1ms | 21.047
| | P99| 10ms| 23ms | 13ms | 132.307
| createUser | Avg| 178ms| 179ms | 1ms | 0.561
| | P99| 468ms| 472ms | 4ms | 0.854
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| deletePost | Avg| 23ms| 22ms | -1ms | -4.334
| | P99| 48ms| 25ms | -23ms | -48.167
| followThreadByUser | Avg| 12ms| 13ms | 1ms | 8.127
| | P99| 25ms| 25ms | 0s | 0.000
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 21ms | 2ms | 10.399
| getAnalytics | Avg| 39ms| 0s | -39ms | -99.970
| | P99| 50ms| 0s | -50ms | -100.503
| getCategoriesForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 37ms| 39ms | 2ms | 5.398
| getChannelMembers | Avg| 2ms| 0s | -2ms | -101.772
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 11.878
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 5.060
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 44ms| 44ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 45ms| 45ms | 0s | 0.000
| | P99| 148ms| 162ms | 14ms | 9.490
| getFileThumbnail | Avg| 43ms| 43ms | 0s | 0.000
| | P99| 114ms| 133ms | 19ms | 16.615
| getFilteredUsersStats | Avg| 9ms| 0s | -9ms | -103.183
| | P99| 10ms| 0s | -10ms | -100.503
| getJobsByType | Avg| 2ms| 1ms | -1ms | -44.479
| | P99| 41ms| 5ms | -36ms | -87.798
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 13ms| 14ms | 1ms | 7.607
| | P99| 92ms| 96ms | 4ms | 4.341
| getPostsForChannelAroundLastUnread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 67ms| 71ms | 4ms | 5.931
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 4.962
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 106ms| 103ms | -3ms | -2.839
| | P99| 480ms| 483ms | 3ms | 0.625
| getPropertyFields | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 15ms| 13ms | -2ms | -13.551
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 3ms | 2ms | 178.925
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.353
| getTeamStats | Avg| 34ms| 45ms | 11ms | 32.120
| | P99| 50ms| 237ms | 187ms | 375.879
| getTeamsForUser | Avg| 1ms| 2ms | 1ms | 67.560
| | P99| 17ms| 19ms | 2ms | 11.653
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.100
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.298
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 4ms | 1ms | 29.525
| | P99| 23ms| 23ms | 0s | 0.000
| getUsersByGroupChannelIds | Avg| 3ms| 0s | -3ms | -102.047
| | P99| 5ms| 0s | -5ms | -101.010
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 2ms | 1ms | 68.116
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 59ms| 0s | -59ms | -100.688
| | P99| 99ms| 0s | -99ms | -99.748
| listCPAFields | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 29ms| 24ms | -5ms | -17.130
| listCPAValues | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -11.811
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 97ms| 85ms | -12ms | -12.394
| | P99| 474ms| 250ms | -224ms | -47.213
| logout | Avg| 23ms| 26ms | 3ms | 12.883
| | P99| 48ms| 49ms | 1ms | 2.080
| patchPost | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 56ms| 49ms | -7ms | -12.612
| removeUserCustomStatus | Avg| 102ms| 99ms | -3ms | -2.928
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 2ms| 1ms | -1ms | -57.757
| | P99| 9ms| 5ms | -4ms | -42.440
| saveReaction | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.063
| searchAllChannels | Avg| 35ms| 34ms | -1ms | -2.857
| | P99| 213ms| 99ms | -114ms | -53.457
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.142
| searchPostsInTeam | Avg| 121ms| 129ms | 8ms | 6.629
| | P99| 966ms| 969ms | 3ms | 0.311
| searchUsers | Avg| 25ms| 26ms | 1ms | 3.932
| | P99| 49ms| 49ms | 0s | 0.000
| setPostReminder | Avg| 21ms| 20ms | -1ms | -4.872
| | P99| 25ms| 48ms | 23ms | 92.523
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 14ms | 1ms | 7.735
| | P99| 25ms| 78ms | 53ms | 213.280
| updateCategoriesForTeamForUser | Avg| 58ms| 51ms | -7ms | -12.036
| | P99| 218ms| 99ms | -119ms | -54.462
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 5ms| 0s | -5ms | -105.859
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 460ms| 455ms | -5ms | -1.086
| | P99| 994ms| 992ms | -2ms | -0.201
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 11ms| 13ms | 2ms | 18.033
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 27ms | 2ms | 8.006
