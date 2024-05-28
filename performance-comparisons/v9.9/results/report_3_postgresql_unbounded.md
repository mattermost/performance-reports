### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.GetDraftsForUser | avg | 3ms | 33ms | 30ms | 1059.66
| DraftStore.Delete | avg | 2ms | 10ms | 8ms | 425.49
| LicenseStore.GetAll | avg | 2ms | 9ms | 7ms | 288.02
| EmojiStore.GetMultipleByName | avg | 6ms | 19ms | 13ms | 229.95
| UserStore.GetProfilesInChannel | avg | 52ms | 129ms | 77ms | 148.90
| PluginStore.Get | avg | 4ms | 10ms | 6ms | 146.27
| CommandWebhookStore.Cleanup | avg | 8ms | 18ms | 10ms | 125.84
| ChannelStore.GetMembersForUserWithPagination | avg | 11ms | 21ms | 10ms | 93.62
| StatusStore.UpdateExpiredDNDStatuses | avg | 4ms | 8ms | 4ms | 93.39
| TokenStore.Cleanup | avg | 10ms | 19ms | 9ms | 90.62
| ThreadStore.Get | avg | 7ms | 12ms | 5ms | 67.78
| RoleStore.ChannelHigherScopedPermissions | avg | 8ms | 13ms | 5ms | 63.99
| ProductNoticesStore.ClearOldNotices | avg | 36ms | 52ms | 16ms | 43.88
| PostStore.GetPostReminderMetadata | avg | 6ms | 8ms | 2ms | 32.32
| PostStore.AnalyticsPostCount | avg | 231ms | 296ms | 65ms | 28.14
| PostStore.SetPostReminder | avg | 19ms | 23ms | 4ms | 21.51
| UserStore.GetByUsername | avg | 10ms | 12ms | 2ms | 19.62
| ComplianceStore.MessageExport | avg | 16ms | 19ms | 3ms | 19.15
| PostStore.Update | avg | 31ms | 35ms | 4ms | 13.02
| FileInfoStore.AttachToPost | avg | 16ms | 18ms | 2ms | 12.51
| ChannelStore.AutocompleteInTeamForSearch | avg | 108ms | 119ms | 11ms | 10.19
| PreferenceStore.Save | avg | 21ms | 23ms | 2ms | 9.46
| ProductNoticesStore.View | avg | 71ms | 76ms | 5ms | 7.01
| ChannelStore.GetSidebarCategory | avg | 36ms | 38ms | 2ms | 5.49
| ChannelStore.SaveMember | avg | 57ms | 60ms | 3ms | 5.27
| TeamStore.SaveMember | avg | 42ms | 44ms | 2ms | 4.72
| ChannelStore.CreateInitialSidebarCategories | avg | 61ms | 63ms | 2ms | 3.30
| UserStore.Save | avg | 84ms | 86ms | 2ms | 2.37
| UserStore.GetAllProfilesInChannel | avg | 423ms | 430ms | 7ms | 1.65
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.GetDraftsForUser | p99 | 5ms | 50ms | 45ms | 909.09
| DraftStore.Delete | p99 | 5ms | 25ms | 20ms | 404.04
| LicenseStore.GetAll | p99 | 10ms | 25ms | 15ms | 153.85
| ChannelStore.GetTeamChannels | p99 | 97ms | 222ms | 125ms | 129.46
| TeamStore.GetTotalMemberCount | p99 | 100ms | 222ms | 122ms | 122.61
| UserStore.GetProfilesInChannel | p99 | 230ms | 490ms | 260ms | 113.17
| UserStore.GetByUsername | p99 | 77ms | 157ms | 80ms | 104.44
| CommandWebhookStore.Cleanup | p99 | 24ms | 49ms | 25ms | 102.46
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 100ms | 50ms | 100.50
| TokenStore.Cleanup | p99 | 49ms | 98ms | 49ms | 100.00
| PostStore.AnalyticsPostCount | p99 | 495ms | 990ms | 495ms | 100.00
| EmojiStore.GetMultipleByName | p99 | 24ms | 48ms | 24ms | 99.59
| PostStore.GetPostReminderMetadata | p99 | 42ms | 83ms | 41ms | 97.62
| ThreadStore.MarkAllAsReadByTeam | p99 | 25ms | 49ms | 24ms | 97.46
| ChannelStore.GetMembersForUserWithPagination | p99 | 25ms | 49ms | 24ms | 97.09
| ThreadStore.Get | p99 | 48ms | 93ms | 45ms | 93.08
| UserAccessTokenStore.GetByToken | p99 | 88ms | 156ms | 68ms | 77.49
| LinkMetadataStore.Save | p99 | 47ms | 83ms | 36ms | 76.73
| RoleStore.ChannelHigherScopedPermissions | p99 | 80ms | 121ms | 41ms | 51.09
| ComplianceStore.MessageExport | p99 | 148ms | 207ms | 59ms | 39.86
| ChannelStore.GetSidebarCategory | p99 | 249ms | 345ms | 96ms | 38.52
| ChannelStore.GetMemberForPost | p99 | 100ms | 129ms | 29ms | 29.04
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 302ms | 380ms | 78ms | 25.79
| ThreadStore.GetTeamsUnreadForUser | p99 | 100ms | 122ms | 22ms | 22.01
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 187ms | 224ms | 37ms | 19.82
| UserStore.UpdateUpdateAt | p99 | 53ms | 63ms | 10ms | 18.91
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 74ms | 87ms | 13ms | 17.45
| UserStore.AutocompleteUsersInChannel | p99 | 317ms | 368ms | 51ms | 16.10
| GroupStore.GetByName | p99 | 70ms | 81ms | 11ms | 15.77
| PostPersistentNotificationStore.Get | p99 | 39ms | 45ms | 6ms | 15.38
| JobStore.Get | p99 | 192ms | 221ms | 29ms | 15.09
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 62ms | 70ms | 8ms | 12.87
| WebhookStore.GetOutgoingByTeam | p99 | 117ms | 130ms | 13ms | 11.11
| UserStore.Save | p99 | 309ms | 342ms | 33ms | 10.67
| UserStore.GetAllProfiles | p99 | 49ms | 54ms | 5ms | 10.11
| PostPriorityStore.GetForPosts | p99 | 154ms | 169ms | 15ms | 9.73
| StatusStore.UpdateExpiredDNDStatuses | p99 | 44ms | 48ms | 4ms | 9.09
| PluginStore.Get | p99 | 44ms | 48ms | 4ms | 8.99
| PostAcknowledgementStore.GetForPosts | p99 | 152ms | 165ms | 13ms | 8.55
| UserStore.IsEmpty | p99 | 35ms | 38ms | 3ms | 8.49
| PostStore.GetPosts | p99 | 71ms | 77ms | 6ms | 8.43
| PostStore.Save | p99 | 275ms | 298ms | 23ms | 8.37
| PluginStore.Delete | p99 | 52ms | 56ms | 4ms | 7.63
| TeamStore.GetMember | p99 | 41ms | 44ms | 3ms | 7.40
| UserStore.UpdateLastLogin | p99 | 59ms | 63ms | 4ms | 6.74
| JobStore.UpdateOptimistically | p99 | 123ms | 131ms | 8ms | 6.50
| TeamStore.GetTeamsByUserId | p99 | 81ms | 86ms | 5ms | 6.19
| FileInfoStore.AttachToPost | p99 | 163ms | 173ms | 10ms | 6.12
| UserStore.GetUnreadCount | p99 | 86ms | 91ms | 5ms | 5.80
| PostStore.Update | p99 | 226ms | 238ms | 12ms | 5.31
| ChannelStore.SaveMember | p99 | 415ms | 437ms | 22ms | 5.31
| ReactionStore.GetForPost | p99 | 78ms | 82ms | 4ms | 5.11
| UserStore.Get | p99 | 79ms | 83ms | 4ms | 5.08
| ThreadStore.MarkAsRead | p99 | 80ms | 84ms | 4ms | 5.03
| ProductNoticesStore.View | p99 | 682ms | 716ms | 34ms | 4.99
| TeamStore.GetAllPage | p99 | 80ms | 84ms | 4ms | 4.98
| ChannelStore.IncrementMentionCount | p99 | 83ms | 87ms | 4ms | 4.82
| PostStore.GetPostsByThread | p99 | 90ms | 94ms | 4ms | 4.43
| ChannelStore.CreateInitialSidebarCategories | p99 | 415ms | 432ms | 17ms | 4.10
| PreferenceStore.Save | p99 | 223ms | 232ms | 9ms | 4.04
| SystemStore.GetByName | p99 | 75ms | 78ms | 3ms | 4.03
| PostStore.GetPostsBefore | p99 | 100ms | 104ms | 4ms | 4.02
| ChannelStore.GetMemberLastViewedAt | p99 | 77ms | 80ms | 3ms | 3.88
| ChannelStore.GetMemberCount | p99 | 186ms | 193ms | 7ms | 3.76
| ThreadStore.UpdateMembership | p99 | 84ms | 87ms | 3ms | 3.59
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 84ms | 87ms | 3ms | 3.56
| PostStore.GetSingle | p99 | 85ms | 88ms | 3ms | 3.53
| ChannelStore.GetByName | p99 | 86ms | 89ms | 3ms | 3.50
| LinkMetadataStore.Get | p99 | 86ms | 89ms | 3ms | 3.47
| ThreadStore.GetMembershipForUser | p99 | 87ms | 90ms | 3ms | 3.45
| ChannelStore.GetGuestCount | p99 | 87ms | 90ms | 3ms | 3.44
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 58ms | 60ms | 2ms | 3.42
| ThreadStore.GetThreadForUser | p99 | 178ms | 184ms | 6ms | 3.37
| SessionStore.GetLRUSessions | p99 | 66ms | 68ms | 2ms | 3.03
| StatusStore.Get | p99 | 67ms | 69ms | 2ms | 2.98
| TeamStore.SaveMember | p99 | 236ms | 243ms | 7ms | 2.96
| SessionStore.Get | p99 | 179ms | 184ms | 5ms | 2.80
| AuditStore.Save | p99 | 78ms | 80ms | 2ms | 2.55
| UserStore.GetForLogin | p99 | 80ms | 82ms | 2ms | 2.50
| TeamStore.Get | p99 | 82ms | 84ms | 2ms | 2.45
| SessionStore.UpdateLastActivityAt | p99 | 84ms | 86ms | 2ms | 2.39
| GroupStore.GetGroups | p99 | 88ms | 90ms | 2ms | 2.27
| ThreadStore.MarkAllAsReadByChannels | p99 | 89ms | 91ms | 2ms | 2.24
| PostStore.GetPostsAfter | p99 | 91ms | 93ms | 2ms | 2.20
| ChannelStore.GetMembersForUser | p99 | 96ms | 98ms | 2ms | 2.08
| PostStore.GetPostsSince | p99 | 197ms | 201ms | 4ms | 2.03
| UserStore.Search | p99 | 229ms | 233ms | 4ms | 1.74
| UserStore.GetAllProfilesInChannel | p99 | 2.157s | 2.194s | 37ms | 1.72
| ChannelStore.CreateDirectChannel | p99 | 479ms | 485ms | 6ms | 1.25
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Upsert | avg | 4ms | 0s | -4ms | -105.54
| ChannelStore.GetChannelsByIds | avg | 12ms | 0s | -12ms | -102.55
| ChannelStore.GetMemberCountsByGroup | avg | 20ms | 0s | -20ms | -102.31
| SystemStore.SaveOrUpdate | avg | 4ms | 0s | -4ms | -100.86
| DraftStore.Get | avg | 38ms | 0s | -38ms | -100.84
| TeamStore.GetMany | avg | 10ms | 0s | -10ms | -100.45
| PostStore.GetPostsByIds | avg | 24ms | 0s | -24ms | -100.07
| PostPersistentNotificationStore.UpdateLastActivity | avg | 8ms | 0s | -8ms | -99.56
| ChannelStore.GetMembers | avg | 19ms | 0s | -19ms | -98.49
| SystemStore.PermanentDeleteByName | avg | 4ms | 0s | -4ms | -95.94
| ProductNoticesStore.GetViews | avg | 6ms | 0s | -6ms | -94.39
| UserStore.AnalyticsGetInactiveUsersCount | avg | 7ms | 1ms | -6ms | -91.99
| RetentionPolicyStore.GetCount | avg | 3ms | 1ms | -2ms | -68.39
| ChannelStore.CreateSidebarCategory | avg | 205ms | 69ms | -136ms | -66.24
| UserStore.GetProfilesNotInChannel | avg | 39ms | 15ms | -24ms | -62.03
| TeamStore.AnalyticsTeamCount | avg | 6ms | 2ms | -4ms | -61.96
| SessionStore.GetSessionsExpired | avg | 9ms | 4ms | -5ms | -53.63
| ChannelStore.AnalyticsTypeCount | avg | 19ms | 9ms | -10ms | -52.81
| JobStore.UpdateStatusOptimistically | avg | 12ms | 6ms | -6ms | -51.83
| UserStore.AnalyticsActiveCount | avg | 51ms | 26ms | -25ms | -48.58
| StatusStore.SaveOrUpdate | avg | 91ms | 51ms | -40ms | -43.85
| UserStore.GetMany | avg | 12ms | 7ms | -5ms | -42.98
| JobStore.GetCountByStatusAndType | avg | 9ms | 5ms | -4ms | -42.53
| BotStore.Get | avg | 10ms | 6ms | -4ms | -38.43
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 25ms | 16ms | -9ms | -36.63
| UserAccessTokenStore.GetByToken | avg | 11ms | 7ms | -4ms | -35.77
| JobStore.Save | avg | 9ms | 6ms | -3ms | -33.49
| JobStore.UpdateStatus | avg | 7ms | 5ms | -2ms | -28.82
| UserStore.Count | avg | 29ms | 22ms | -7ms | -23.96
| ThreadStore.MarkAllAsReadByTeam | avg | 11ms | 9ms | -2ms | -18.46
| PostStore.SearchPostsForUser | avg | 291ms | 246ms | -45ms | -15.47
| ChannelStore.Save | avg | 39ms | 34ms | -5ms | -12.86
| PreferenceStore.DeleteCategoryAndName | avg | 16ms | 14ms | -2ms | -12.40
| UserStore.Update | avg | 24ms | 21ms | -3ms | -12.37
| PostStore.Delete | avg | 46ms | 41ms | -5ms | -10.85
| TeamStore.GetActiveMemberCount | avg | 77ms | 69ms | -8ms | -10.42
| ChannelStore.UpdateSidebarCategories | avg | 140ms | 126ms | -14ms | -9.97
| TeamStore.GetTotalMemberCount | avg | 64ms | 60ms | -4ms | -6.29
| ChannelStore.Autocomplete | avg | 59ms | 57ms | -2ms | -3.39
| ChannelStore.CreateDirectChannel | avg | 72ms | 70ms | -2ms | -2.76
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 125ms | 122ms | -3ms | -2.40
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 25ms | 0s | -25ms | -101.83
| TeamStore.GetMany | p99 | 25ms | 0s | -25ms | -101.21
| ProductNoticesStore.GetViews | p99 | 25ms | 0s | -25ms | -101.14
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.94
| PostStore.GetPostsByIds | p99 | 50ms | 0s | -50ms | -100.76
| DraftStore.Get | p99 | 50ms | 0s | -50ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 122ms | 0s | -122ms | -100.21
| ChannelStore.GetMembers | p99 | 49ms | 0s | -49ms | -99.16
| ChannelStore.GetChannelsByIds | p99 | 48ms | 0s | -48ms | -98.97
| BotStore.Get | p99 | 208ms | 24ms | -184ms | -88.46
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 25ms | 5ms | -20ms | -81.47
| TeamStore.AnalyticsTeamCount | p99 | 24ms | 5ms | -19ms | -78.35
| JobStore.UpdateStatusOptimistically | p99 | 154ms | 35ms | -119ms | -77.27
| JobStore.GetCountByStatusAndType | p99 | 175ms | 57ms | -118ms | -67.43
| JobStore.UpdateStatus | p99 | 69ms | 23ms | -46ms | -67.15
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 232ms | 92ms | -140ms | -60.34
| UserStore.GetProfilesNotInChannel | p99 | 239ms | 95ms | -144ms | -60.13
| PostStore.GetPostReminders | p99 | 214ms | 88ms | -126ms | -58.88
| PostStore.SetPostReminder | p99 | 224ms | 96ms | -128ms | -57.02
| PluginStore.List | p99 | 169ms | 77ms | -92ms | -54.44
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.735s | 832ms | -903ms | -52.04
| UserStore.Count | p99 | 195ms | 95ms | -100ms | -51.41
| RetentionPolicyStore.GetCount | p99 | 10ms | 5ms | -5ms | -51.02
| ChannelStore.CreateSidebarCategory | p99 | 495ms | 245ms | -250ms | -50.50
| SessionStore.GetSessionsExpired | p99 | 48ms | 24ms | -24ms | -50.00
| JobStore.Save | p99 | 84ms | 42ms | -42ms | -49.85
| UserStore.AnalyticsActiveCount | p99 | 99ms | 50ms | -49ms | -49.66
| PreferenceStore.DeleteCategoryAndName | p99 | 94ms | 48ms | -46ms | -48.94
| ChannelStore.AnalyticsTypeCount | p99 | 49ms | 25ms | -24ms | -48.92
| UserStore.GetMany | p99 | 90ms | 48ms | -42ms | -46.67
| PostPersistentNotificationStore.DeleteExpired | p99 | 45ms | 24ms | -21ms | -46.54
| ChannelStore.UpdateSidebarCategories | p99 | 865ms | 473ms | -392ms | -45.32
| PostPriorityStore.GetForPost | p99 | 88ms | 50ms | -38ms | -43.38
| PostAcknowledgementStore.GetForPost | p99 | 84ms | 48ms | -36ms | -42.93
| SessionStore.Remove | p99 | 82ms | 47ms | -35ms | -42.68
| UserStore.Update | p99 | 215ms | 151ms | -64ms | -29.74
| StatusStore.GetByIds | p99 | 137ms | 99ms | -38ms | -27.84
| JobStore.GetNewestJobByStatusesAndType | p99 | 79ms | 62ms | -17ms | -21.42
| PluginStore.SetWithOptions | p99 | 121ms | 98ms | -23ms | -18.97
| StatusStore.SaveOrUpdate | p99 | 963ms | 842ms | -121ms | -12.56
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 83ms | 77ms | -6ms | -7.25
| ChannelStore.GetChannelUnread | p99 | 97ms | 90ms | -7ms | -7.21
| JobStore.GetAllByStatus | p99 | 153ms | 143ms | -10ms | -6.54
| ThreadStore.GetThreadFollowers | p99 | 87ms | 82ms | -5ms | -5.74
| ChannelStore.GetChannelsByUser | p99 | 98ms | 93ms | -5ms | -5.10
| ChannelStore.Save | p99 | 245ms | 233ms | -12ms | -4.90
| PostStore.GetPostIdAfterTime | p99 | 66ms | 63ms | -3ms | -4.58
| FileInfoStore.SetContent | p99 | 219ms | 211ms | -8ms | -3.66
| SessionStore.Save | p99 | 112ms | 108ms | -4ms | -3.56
| ThreadStore.GetTotalThreads | p99 | 87ms | 84ms | -3ms | -3.45
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 89ms | 86ms | -3ms | -3.38
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 463ms | 448ms | -15ms | -3.24
| ChannelStore.GetPinnedPostCount | p99 | 94ms | 91ms | -3ms | -3.20
| FileInfoStore.Save | p99 | 99ms | 96ms | -3ms | -3.04
| ChannelStore.GetPublicChannelsForTeam | p99 | 169ms | 164ms | -5ms | -2.96
| PostPersistentNotificationStore.GetSingle | p99 | 82ms | 80ms | -2ms | -2.43
| TeamStore.GetTeamsForUser | p99 | 85ms | 83ms | -2ms | -2.35
| StatusStore.UpdateLastActivityAt | p99 | 87ms | 85ms | -2ms | -2.29
| ChannelStore.Autocomplete | p99 | 236ms | 231ms | -5ms | -2.12
| TeamStore.GetActiveMemberCount | p99 | 240ms | 236ms | -4ms | -1.67
| PostStore.Delete | p99 | 243ms | 239ms | -4ms | -1.65
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 9ms | 18ms | 9ms | 96.58
| followThreadByUser | avg | 33ms | 65ms | 32ms | 96.15
| setPostReminder | avg | 52ms | 70ms | 18ms | 34.92
| logout | avg | 153ms | 181ms | 28ms | 18.29
| unfollowThreadByUser | avg | 57ms | 64ms | 7ms | 12.38
| autocompleteChannelsForTeamForSearch | avg | 108ms | 120ms | 12ms | 11.11
| updatePreferences | avg | 33ms | 36ms | 3ms | 9.04
| createGroupChannel | avg | 649ms | 701ms | 52ms | 8.02
| getPostThread | avg | 53ms | 56ms | 3ms | 5.62
| updateReadStateThreadByUser | avg | 126ms | 132ms | 6ms | 4.78
| addTeamMember | avg | 1.3s | 1.356s | 56ms | 4.31
| getPostsForChannelAroundLastUnread | avg | 47ms | 49ms | 2ms | 4.24
| createUser | avg | 237ms | 245ms | 8ms | 3.37
| autocompleteUsers | avg | 62ms | 64ms | 2ms | 3.20
| createPost | avg | 819ms | 843ms | 24ms | 2.93
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 214ms | 425ms | 211ms | 98.60
| updateReadStateAllThreadsByUser | p99 | 25ms | 49ms | 24ms | 97.46
| setPostReminder | p99 | 237ms | 457ms | 220ms | 92.73
| logout | p99 | 482ms | 860ms | 378ms | 78.42
| createGroupChannel | p99 | 2.396s | 3.8s | 1.404s | 58.59
| getUserStatusesByIds | p99 | 24ms | 30ms | 6ms | 24.73
| autocompleteUsers | p99 | 253ms | 315ms | 62ms | 24.46
| addTeamMember | p99 | 5.193s | 6.274s | 1.081s | 20.82
| updatePreferences | p99 | 248ms | 297ms | 49ms | 19.79
| createUser | p99 | 1.386s | 1.602s | 216ms | 15.58
| getFilePreview | p99 | 248ms | 275ms | 27ms | 10.87
| getUsersByNames | p99 | 102ms | 111ms | 9ms | 8.82
| updateReadStateThreadByUser | p99 | 776ms | 827ms | 51ms | 6.57
| getChannelStats | p99 | 97ms | 103ms | 6ms | 6.17
| getTeamsForUser | p99 | 82ms | 87ms | 5ms | 6.09
| getUsers | p99 | 193ms | 204ms | 11ms | 5.70
| viewChannel | p99 | 369ms | 387ms | 18ms | 4.87
| getChannelsForTeamForUser | p99 | 117ms | 121ms | 4ms | 3.42
| getTeamsUnreadForUser | p99 | 183ms | 189ms | 6ms | 3.28
| getChannelMembersForTeamForUser | p99 | 99ms | 102ms | 3ms | 3.04
| addChannelMember | p99 | 2.336s | 2.385s | 49ms | 2.10
| saveReaction | p99 | 242ms | 247ms | 5ms | 2.06
| getTeamMembersForUser | p99 | 98ms | 100ms | 2ms | 2.04
| getPostsForChannelAroundLastUnread | p99 | 440ms | 448ms | 8ms | 1.82
| getClientConfig | p99 | 221ms | 225ms | 4ms | 1.81
| searchUsers | p99 | 232ms | 236ms | 4ms | 1.72
| getFileThumbnail | p99 | 241ms | 245ms | 4ms | 1.66
| getTeamStats | p99 | 240ms | 243ms | 3ms | 1.25
| uploadFileStream | p99 | 1.852s | 1.871s | 19ms | 1.03
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | avg | 6ms | 0s | -6ms | -108.49
| getPrevTrialLicense | avg | 4ms | 0s | -4ms | -105.02
| deleteDraft | avg | 22ms | 0s | -22ms | -101.70
| channelMemberCountsByGroup | avg | 20ms | 0s | -20ms | -101.56
| getDrafts | avg | 3ms | 0s | -3ms | -100.51
| getProductNotices | avg | 11ms | 0s | -11ms | -100.24
| getChannelMembers | avg | 20ms | 0s | -20ms | -99.89
| getLicenseSelfServeStatus | avg | 105ms | 0s | -105ms | -99.79
| getGroups | avg | 36ms | 0s | -36ms | -98.79
| getFilteredUsersStats | avg | 24ms | 0s | -24ms | -98.62
| getAnalytics | avg | 167ms | 30ms | -137ms | -82.03
| createCategoryForTeamForUser | avg | 247ms | 97ms | -150ms | -60.68
| upsertDraft | avg | 13ms | 8ms | -5ms | -37.59
| getChannel | avg | 25ms | 18ms | -7ms | -28.55
| createChannel | avg | 562ms | 445ms | -117ms | -20.81
| updateReadStateAllThreadsByUser | avg | 11ms | 9ms | -2ms | -18.28
| deletePost | avg | 77ms | 64ms | -13ms | -16.92
| searchPostsInTeam | avg | 323ms | 273ms | -50ms | -15.49
| getChannelMembersForUser | avg | 13ms | 11ms | -2ms | -14.94
| removeUserCustomStatus | avg | 315ms | 286ms | -29ms | -9.20
| updateCategoriesForTeamForUser | avg | 227ms | 207ms | -20ms | -8.81
| createDirectChannel | avg | 478ms | 439ms | -39ms | -8.15
| addChannelMember | avg | 492ms | 459ms | -33ms | -6.71
| getPublicChannelsForTeam | avg | 34ms | 32ms | -2ms | -5.88
| getProfileImage | avg | 84ms | 81ms | -3ms | -3.58
| searchAllChannels | avg | 60ms | 58ms | -2ms | -3.35
| getPostsForChannel | avg | 97ms | 94ms | -3ms | -3.08
| patchPost | avg | 110ms | 108ms | -2ms | -1.81
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 10ms | 0s | -10ms | -101.52
| deleteDraft | p99 | 50ms | 0s | -50ms | -101.01
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 50ms | 0s | -50ms | -100.98
| getSelfHostedProducts | p99 | 5ms | 0s | -5ms | -100.95
| createEmoji | p99 | 10ms | 0s | -10ms | -100.63
| getProductNotices | p99 | 25ms | 0s | -25ms | -100.60
| getGroups | p99 | 99ms | 0s | -99ms | -100.00
| getLicenseSelfServeStatus | p99 | 248ms | 0s | -248ms | -99.80
| channelMemberCountsByGroup | p99 | 123ms | 0s | -123ms | -99.80
| getChannelMembers | p99 | 49ms | 0s | -49ms | -99.16
| getAnalytics | p99 | 490ms | 98ms | -392ms | -80.00
| updateCategoriesForTeamForUser | p99 | 2.103s | 917ms | -1.186s | -56.41
| autocompleteChannelsForTeamForSearch | p99 | 1.735s | 832ms | -903ms | -52.04
| createCategoryForTeamForUser | p99 | 495ms | 245ms | -250ms | -50.50
| getRolesByNames | p99 | 48ms | 25ms | -23ms | -47.42
| deletePost | p99 | 440ms | 244ms | -196ms | -44.55
| getChannel | p99 | 264ms | 174ms | -90ms | -34.07
| patchPost | p99 | 945ms | 769ms | -176ms | -18.62
| getPublicChannelsForTeam | p99 | 214ms | 181ms | -33ms | -15.45
| login | p99 | 1.225s | 1.085s | -140ms | -11.43
| getChannelUnread | p99 | 104ms | 98ms | -6ms | -5.75
| unfollowThreadByUser | p99 | 447ms | 424ms | -23ms | -5.14
| removeUserCustomStatus | p99 | 996ms | 954ms | -42ms | -4.21
| getChannelsForUser | p99 | 99ms | 95ms | -4ms | -4.02
| getPostsForChannel | p99 | 932ms | 913ms | -19ms | -2.04
| searchAllChannels | p99 | 237ms | 233ms | -4ms | -1.69
| createChannel | p99 | 2.395s | 2.358s | -37ms | -1.54
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 78ms| 80ms | 2ms | 2.550
| BotStore.Get |  Avg| 10ms| 6ms | -4ms | -38.432
| |  P99| 208ms| 24ms | -184ms | -88.462
| BotStore.Save |  Avg| 4ms| 3ms | -1ms | -27.576
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 125ms| 122ms | -3ms | -2.401
| |  P99| 463ms| 448ms | -15ms | -3.241
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 58ms| 60ms | 2ms | 3.422
| ChannelStore.AnalyticsTypeCount |  Avg| 19ms| 9ms | -10ms | -52.806
| |  P99| 49ms| 25ms | -24ms | -48.919
| ChannelStore.Autocomplete |  Avg| 59ms| 57ms | -2ms | -3.389
| |  P99| 236ms| 231ms | -5ms | -2.118
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 108ms| 119ms | 11ms | 10.192
| |  P99| 1.735s| 832ms | -903ms | -52.045
| ChannelStore.CreateDirectChannel |  Avg| 72ms| 70ms | -2ms | -2.761
| |  P99| 479ms| 485ms | 6ms | 1.252
| ChannelStore.CreateInitialSidebarCategories |  Avg| 61ms| 63ms | 2ms | 3.302
| |  P99| 415ms| 432ms | 17ms | 4.101
| ChannelStore.CreateSidebarCategory |  Avg| 205ms| 69ms | -136ms | -66.242
| |  P99| 495ms| 245ms | -250ms | -50.505
| ChannelStore.Get |  Avg| 11ms| 12ms | 1ms | 8.884
| |  P99| 96ms| 97ms | 1ms | 1.043
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 28ms| 29ms | 1ms | 3.542
| |  P99| 187ms| 224ms | 37ms | 19.818
| ChannelStore.GetAllChannelMembersForUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.108
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 302ms| 380ms | 78ms | 25.785
| ChannelStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 86ms| 89ms | 3ms | 3.501
| ChannelStore.GetChannelUnread |  Avg| 11ms| 10ms | -1ms | -9.135
| |  P99| 97ms| 90ms | -7ms | -7.212
| ChannelStore.GetChannels |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 99ms | 1ms | 1.016
| ChannelStore.GetChannelsByIds |  Avg| 12ms| 0s | -12ms | -102.552
| |  P99| 48ms| 0s | -48ms | -98.969
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 93ms | -5ms | -5.102
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 10ms | 1ms | 10.528
| |  P99| 92ms| 93ms | 1ms | 1.092
| ChannelStore.GetFileCount |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 96ms| 96ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 90ms | 3ms | 3.438
| ChannelStore.GetMember |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.095
| ChannelStore.GetMemberCount |  Avg| 34ms| 35ms | 1ms | 2.948
| |  P99| 186ms| 193ms | 7ms | 3.765
| ChannelStore.GetMemberCountsByGroup |  Avg| 20ms| 0s | -20ms | -102.309
| |  P99| 122ms| 0s | -122ms | -100.206
| ChannelStore.GetMemberForPost |  Avg| 15ms| 16ms | 1ms | 6.623
| |  P99| 100ms| 129ms | 29ms | 29.041
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 77ms| 80ms | 3ms | 3.875
| ChannelStore.GetMembers |  Avg| 19ms| 0s | -19ms | -98.491
| |  P99| 49ms| 0s | -49ms | -99.155
| ChannelStore.GetMembersForUser |  Avg| 11ms| 12ms | 1ms | 8.808
| |  P99| 96ms| 98ms | 2ms | 2.078
| ChannelStore.GetMembersForUserWithPagination |  Avg| 11ms| 21ms | 10ms | 93.616
| |  P99| 25ms| 49ms | 24ms | 97.092
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 94ms| 91ms | -3ms | -3.201
| ChannelStore.GetPublicChannelsForTeam |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 169ms| 164ms | -5ms | -2.959
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 43ms| 43ms | 0s | 0.000
| |  P99| 231ms| 232ms | 1ms | 0.434
| ChannelStore.GetSidebarCategory |  Avg| 36ms| 38ms | 2ms | 5.486
| |  P99| 249ms| 345ms | 96ms | 38.515
| ChannelStore.GetTeamChannels |  Avg| 38ms| 37ms | -1ms | -2.647
| |  P99| 97ms| 222ms | 125ms | 129.459
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 8ms | 1ms | 13.822
| |  P99| 83ms| 87ms | 4ms | 4.816
| ChannelStore.Save |  Avg| 39ms| 34ms | -5ms | -12.859
| |  P99| 245ms| 233ms | -12ms | -4.904
| ChannelStore.SaveMember |  Avg| 57ms| 60ms | 3ms | 5.267
| |  P99| 415ms| 437ms | 22ms | 5.305
| ChannelStore.SearchGroupChannels |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 141ms| 142ms | 1ms | 0.711
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 90ms | 1ms | 1.127
| ChannelStore.UpdateSidebarCategories |  Avg| 140ms| 126ms | -14ms | -9.973
| |  P99| 865ms| 473ms | -392ms | -45.318
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 8ms | 1ms | 14.428
| |  P99| 74ms| 87ms | 13ms | 17.452
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.023
| CommandWebhookStore.Cleanup |  Avg| 8ms| 18ms | 10ms | 125.835
| |  P99| 24ms| 49ms | 25ms | 102.457
| ComplianceStore.MessageExport |  Avg| 16ms| 19ms | 3ms | 19.147
| |  P99| 148ms| 207ms | 59ms | 39.865
| DraftStore.Delete |  Avg| 2ms| 10ms | 8ms | 425.488
| |  P99| 5ms| 25ms | 20ms | 404.040
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 25ms| 16ms | -9ms | -36.632
| |  P99| 232ms| 92ms | -140ms | -60.345
| DraftStore.Get |  Avg| 38ms| 0s | -38ms | -100.836
| |  P99| 50ms| 0s | -50ms | -100.503
| DraftStore.GetDraftsForUser |  Avg| 3ms| 33ms | 30ms | 1059.659
| |  P99| 5ms| 50ms | 45ms | 909.091
| DraftStore.Upsert |  Avg| 4ms| 0s | -4ms | -105.536
| |  P99| 5ms| 0s | -5ms | -100.942
| EmojiStore.GetByName |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 90ms | 1ms | 1.120
| EmojiStore.GetMultipleByName |  Avg| 6ms| 19ms | 13ms | 229.948
| |  P99| 24ms| 48ms | 24ms | 99.585
| FileInfoStore.AttachToPost |  Avg| 16ms| 18ms | 2ms | 12.512
| |  P99| 163ms| 173ms | 10ms | 6.119
| FileInfoStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 97ms | 1ms | 1.042
| FileInfoStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 90ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 12ms| 13ms | 1ms | 8.250
| |  P99| 99ms| 96ms | -3ms | -3.038
| FileInfoStore.SetContent |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 219ms| 211ms | -8ms | -3.660
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 70ms | 8ms | 12.872
| GroupStore.GetByName |  Avg| 6ms| 7ms | 1ms | 16.080
| |  P99| 70ms| 81ms | 11ms | 15.767
| GroupStore.GetGroups |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.274
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 192ms| 221ms | 29ms | 15.088
| JobStore.GetAllByStatus |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 153ms| 143ms | -10ms | -6.539
| JobStore.GetCountByStatusAndType |  Avg| 9ms| 5ms | -4ms | -42.528
| |  P99| 175ms| 57ms | -118ms | -67.429
| JobStore.GetNewestJobByStatusesAndType |  Avg| 7ms| 6ms | -1ms | -14.985
| |  P99| 79ms| 62ms | -17ms | -21.417
| JobStore.Save |  Avg| 9ms| 6ms | -3ms | -33.490
| |  P99| 84ms| 42ms | -42ms | -49.852
| JobStore.UpdateOptimistically |  Avg| 13ms| 12ms | -1ms | -7.513
| |  P99| 123ms| 131ms | 8ms | 6.504
| JobStore.UpdateStatus |  Avg| 7ms| 5ms | -2ms | -28.825
| |  P99| 69ms| 23ms | -46ms | -67.151
| JobStore.UpdateStatusOptimistically |  Avg| 12ms| 6ms | -6ms | -51.827
| |  P99| 154ms| 35ms | -119ms | -77.269
| LicenseStore.GetAll |  Avg| 2ms| 9ms | 7ms | 288.022
| |  P99| 10ms| 25ms | 15ms | 153.846
| LinkMetadataStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 89ms | 3ms | 3.469
| LinkMetadataStore.Save |  Avg| 6ms| 7ms | 1ms | 16.663
| |  P99| 47ms| 83ms | 36ms | 76.732
| PluginStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 52ms| 56ms | 4ms | 7.629
| PluginStore.Get |  Avg| 4ms| 10ms | 6ms | 146.265
| |  P99| 44ms| 48ms | 4ms | 8.989
| PluginStore.List |  Avg| 12ms| 13ms | 1ms | 8.426
| |  P99| 169ms| 77ms | -92ms | -54.438
| PluginStore.SetWithOptions |  Avg| 11ms| 10ms | -1ms | -9.217
| |  P99| 121ms| 98ms | -23ms | -18.972
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 48ms | -36ms | -42.930
| PostAcknowledgementStore.GetForPosts |  Avg| 12ms| 13ms | 1ms | 8.247
| |  P99| 152ms| 165ms | 13ms | 8.554
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 24ms | -21ms | -46.537
| PostPersistentNotificationStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 45ms | 6ms | 15.384
| PostPersistentNotificationStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 80ms | -2ms | -2.433
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 8ms| 0s | -8ms | -99.561
| |  P99| 25ms| 0s | -25ms | -101.829
| PostPriorityStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -12.672
| |  P99| 88ms| 50ms | -38ms | -43.379
| PostPriorityStore.GetForPosts |  Avg| 12ms| 13ms | 1ms | 8.015
| |  P99| 154ms| 169ms | 15ms | 9.729
| PostStore.AnalyticsPostCount |  Avg| 231ms| 296ms | 65ms | 28.143
| |  P99| 495ms| 990ms | 495ms | 100.000
| PostStore.Delete |  Avg| 46ms| 41ms | -5ms | -10.851
| |  P99| 243ms| 239ms | -4ms | -1.647
| PostStore.Get |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 217ms| 216ms | -1ms | -0.461
| PostStore.GetEtag |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 6ms | 1ms | 18.438
| |  P99| 66ms| 63ms | -3ms | -4.577
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 90ms | 1ms | 1.126
| PostStore.GetPostReminderMetadata |  Avg| 6ms| 8ms | 2ms | 32.316
| |  P99| 42ms| 83ms | 41ms | 97.620
| PostStore.GetPostReminders |  Avg| 14ms| 15ms | 1ms | 6.908
| |  P99| 214ms| 88ms | -126ms | -58.879
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 71ms| 77ms | 6ms | 8.428
| PostStore.GetPostsAfter |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 91ms| 93ms | 2ms | 2.202
| PostStore.GetPostsBefore |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 100ms| 104ms | 4ms | 4.017
| PostStore.GetPostsByIds |  Avg| 24ms| 0s | -24ms | -100.068
| |  P99| 50ms| 0s | -50ms | -100.755
| PostStore.GetPostsByThread |  Avg| 14ms| 15ms | 1ms | 7.191
| |  P99| 90ms| 94ms | 4ms | 4.429
| PostStore.GetPostsSince |  Avg| 25ms| 26ms | 1ms | 3.976
| |  P99| 197ms| 201ms | 4ms | 2.032
| PostStore.GetSingle |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 85ms| 88ms | 3ms | 3.531
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 31ms| 32ms | 1ms | 3.229
| |  P99| 275ms| 298ms | 23ms | 8.371
| PostStore.SearchPostsForUser |  Avg| 291ms| 246ms | -45ms | -15.473
| |  P99| 2.4s| 2.391s | -9ms | -0.375
| PostStore.SetPostReminder |  Avg| 19ms| 23ms | 4ms | 21.512
| |  P99| 224ms| 96ms | -128ms | -57.016
| PostStore.Update |  Avg| 31ms| 35ms | 4ms | 13.025
| |  P99| 226ms| 238ms | 12ms | 5.313
| PreferenceStore.DeleteCategoryAndName |  Avg| 16ms| 14ms | -2ms | -12.397
| |  P99| 94ms| 48ms | -46ms | -48.936
| PreferenceStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 97ms| 98ms | 1ms | 1.032
| PreferenceStore.GetAll |  Avg| 8ms| 9ms | 1ms | 11.849
| |  P99| 90ms| 89ms | -1ms | -1.113
| PreferenceStore.Save |  Avg| 21ms| 23ms | 2ms | 9.464
| |  P99| 223ms| 232ms | 9ms | 4.043
| ProductNoticesStore.ClearOldNotices |  Avg| 36ms| 52ms | 16ms | 43.878
| |  P99| 50ms| 100ms | 50ms | 100.503
| ProductNoticesStore.GetViews |  Avg| 6ms| 0s | -6ms | -94.387
| |  P99| 25ms| 0s | -25ms | -101.140
| ProductNoticesStore.View |  Avg| 71ms| 76ms | 5ms | 7.009
| |  P99| 682ms| 716ms | 34ms | 4.985
| ReactionStore.GetForPost |  Avg| 9ms| 10ms | 1ms | 11.320
| |  P99| 78ms| 82ms | 4ms | 5.110
| RetentionPolicyStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 3ms| 1ms | -2ms | -68.385
| |  P99| 10ms| 5ms | -5ms | -51.020
| RoleStore.ChannelHigherScopedPermissions |  Avg| 8ms| 13ms | 5ms | 63.990
| |  P99| 80ms| 121ms | 41ms | 51.090
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 14ms| 15ms | 1ms | 6.988
| |  P99| 179ms| 184ms | 5ms | 2.799
| SessionStore.GetLRUSessions |  Avg| 6ms| 7ms | 1ms | 15.704
| |  P99| 66ms| 68ms | 2ms | 3.025
| SessionStore.GetSessionsExpired |  Avg| 9ms| 4ms | -5ms | -53.632
| |  P99| 48ms| 24ms | -24ms | -50.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 77ms | -6ms | -7.245
| SessionStore.Remove |  Avg| 9ms| 10ms | 1ms | 10.777
| |  P99| 82ms| 47ms | -35ms | -42.683
| SessionStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 112ms| 108ms | -4ms | -3.559
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 10ms | 1ms | 10.648
| |  P99| 84ms| 86ms | 2ms | 2.394
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 67ms| 69ms | 2ms | 2.978
| StatusStore.GetByIds |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 137ms| 99ms | -38ms | -27.839
| StatusStore.SaveOrUpdate |  Avg| 91ms| 51ms | -40ms | -43.851
| |  P99| 963ms| 842ms | -121ms | -12.560
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 8ms | 4ms | 93.392
| |  P99| 44ms| 48ms | 4ms | 9.091
| StatusStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 85ms | -2ms | -2.295
| SystemStore.GetByName |  Avg| 5ms| 6ms | 1ms | 18.195
| |  P99| 75ms| 78ms | 3ms | 4.026
| SystemStore.PermanentDeleteByName |  Avg| 4ms| 0s | -4ms | -95.940
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 4ms| 0s | -4ms | -100.858
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 2ms | -4ms | -61.963
| |  P99| 24ms| 5ms | -19ms | -78.348
| TeamStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 84ms | 2ms | 2.452
| TeamStore.GetActiveMemberCount |  Avg| 77ms| 69ms | -8ms | -10.422
| |  P99| 240ms| 236ms | -4ms | -1.670
| TeamStore.GetAllPage |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 84ms | 4ms | 4.976
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 87ms | 3ms | 3.556
| TeamStore.GetMany |  Avg| 10ms| 0s | -10ms | -100.450
| |  P99| 25ms| 0s | -25ms | -101.215
| TeamStore.GetMember |  Avg| 3ms| 4ms | 1ms | 28.993
| |  P99| 41ms| 44ms | 3ms | 7.398
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 8ms | 1ms | 14.105
| |  P99| 81ms| 86ms | 5ms | 6.191
| TeamStore.GetTeamsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 83ms | -2ms | -2.352
| TeamStore.GetTotalMemberCount |  Avg| 64ms| 60ms | -4ms | -6.286
| |  P99| 100ms| 222ms | 122ms | 122.613
| TeamStore.SaveMember |  Avg| 42ms| 44ms | 2ms | 4.718
| |  P99| 236ms| 243ms | 7ms | 2.963
| ThreadStore.Get |  Avg| 7ms| 12ms | 5ms | 67.784
| |  P99| 48ms| 93ms | 45ms | 93.083
| ThreadStore.GetMembershipForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 90ms | 3ms | 3.454
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 12ms | 1ms | 8.985
| |  P99| 100ms| 122ms | 22ms | 22.015
| ThreadStore.GetThreadFollowers |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 82ms | -5ms | -5.736
| ThreadStore.GetThreadForUser |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 178ms| 184ms | 6ms | 3.372
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 96ms| 97ms | 1ms | 1.039
| ThreadStore.GetThreadsForUser |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 99ms| 100ms | 1ms | 1.007
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 84ms | -3ms | -3.454
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 9ms | 1ms | 11.991
| |  P99| 86ms| 85ms | -1ms | -1.161
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 84ms | -1ms | -1.170
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 86ms | -3ms | -3.384
| ThreadStore.MaintainMembership |  Avg| 18ms| 19ms | 1ms | 5.428
| |  P99| 210ms| 212ms | 2ms | 0.953
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 91ms | 2ms | 2.237
| ThreadStore.MarkAllAsReadByTeam |  Avg| 11ms| 9ms | -2ms | -18.457
| |  P99| 25ms| 49ms | 24ms | 97.461
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 80ms| 84ms | 4ms | 5.027
| ThreadStore.UpdateMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 84ms| 87ms | 3ms | 3.589
| TokenStore.Cleanup |  Avg| 10ms| 19ms | 9ms | 90.621
| |  P99| 49ms| 98ms | 49ms | 100.000
| UserAccessTokenStore.GetByToken |  Avg| 11ms| 7ms | -4ms | -35.768
| |  P99| 88ms| 156ms | 68ms | 77.492
| UserStore.AnalyticsActiveCount |  Avg| 51ms| 26ms | -25ms | -48.579
| |  P99| 99ms| 50ms | -49ms | -49.661
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 7ms| 1ms | -6ms | -91.993
| |  P99| 25ms| 5ms | -20ms | -81.466
| UserStore.AutocompleteUsersInChannel |  Avg| 72ms| 73ms | 1ms | 1.397
| |  P99| 317ms| 368ms | 51ms | 16.104
| UserStore.Count |  Avg| 29ms| 22ms | -7ms | -23.965
| |  P99| 195ms| 95ms | -100ms | -51.414
| UserStore.Get |  Avg| 6ms| 7ms | 1ms | 15.524
| |  P99| 79ms| 83ms | 4ms | 5.080
| UserStore.GetAllProfiles |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 49ms| 54ms | 5ms | 10.113
| UserStore.GetAllProfilesInChannel |  Avg| 423ms| 430ms | 7ms | 1.653
| |  P99| 2.157s| 2.194s | 37ms | 1.715
| UserStore.GetByUsername |  Avg| 10ms| 12ms | 2ms | 19.622
| |  P99| 77ms| 157ms | 80ms | 104.439
| UserStore.GetForLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 82ms | 2ms | 2.504
| UserStore.GetMany |  Avg| 12ms| 7ms | -5ms | -42.984
| |  P99| 90ms| 48ms | -42ms | -46.666
| UserStore.GetProfileByIds |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 97ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 11ms| 12ms | 1ms | 8.747
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 52ms| 129ms | 77ms | 148.904
| |  P99| 230ms| 490ms | 260ms | 113.166
| UserStore.GetProfilesNotInChannel |  Avg| 39ms| 15ms | -24ms | -62.031
| |  P99| 239ms| 95ms | -144ms | -60.125
| UserStore.GetUnreadCount |  Avg| 9ms| 10ms | 1ms | 11.233
| |  P99| 86ms| 91ms | 5ms | 5.802
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 38ms | 3ms | 8.486
| UserStore.Save |  Avg| 84ms| 86ms | 2ms | 2.370
| |  P99| 309ms| 342ms | 33ms | 10.668
| UserStore.Search |  Avg| 53ms| 53ms | 0s | 0.000
| |  P99| 229ms| 233ms | 4ms | 1.744
| UserStore.Update |  Avg| 24ms| 21ms | -3ms | -12.373
| |  P99| 215ms| 151ms | -64ms | -29.740
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 78ms | -1ms | -1.259
| UserStore.UpdateLastLogin |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 59ms| 63ms | 4ms | 6.744
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 53ms| 63ms | 10ms | 18.911
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.273
| WebhookStore.GetOutgoingByTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 117ms| 130ms | 13ms | 11.113
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 492ms| 459ms | -33ms | -6.712
| | P99| 2.336s| 2.385s | 49ms | 2.098
| addTeamMember | Avg| 1.3s| 1.356s | 56ms | 4.307
| | P99| 5.193s| 6.274s | 1.081s | 20.818
| autocompleteChannelsForTeamForSearch | Avg| 108ms| 120ms | 12ms | 11.112
| | P99| 1.735s| 832ms | -903ms | -52.045
| autocompleteUsers | Avg| 62ms| 64ms | 2ms | 3.202
| | P99| 253ms| 315ms | 62ms | 24.464
| channelMemberCountsByGroup | Avg| 20ms| 0s | -20ms | -101.564
| | P99| 123ms| 0s | -123ms | -99.798
| createCategoryForTeamForUser | Avg| 247ms| 97ms | -150ms | -60.675
| | P99| 495ms| 245ms | -250ms | -50.505
| createChannel | Avg| 562ms| 445ms | -117ms | -20.806
| | P99| 2.395s| 2.358s | -37ms | -1.545
| createDirectChannel | Avg| 478ms| 439ms | -39ms | -8.153
| | P99| 2.249s| 2.244s | -5ms | -0.222
| createEmoji | Avg| 6ms| 0s | -6ms | -108.493
| | P99| 10ms| 0s | -10ms | -100.629
| createGroupChannel | Avg| 649ms| 701ms | 52ms | 8.016
| | P99| 2.396s| 3.8s | 1.404s | 58.585
| createPost | Avg| 819ms| 843ms | 24ms | 2.930
| | P99| 4.407s| 4.4s | -7ms | -0.159
| createUser | Avg| 237ms| 245ms | 8ms | 3.369
| | P99| 1.386s| 1.602s | 216ms | 15.584
| deleteDraft | Avg| 22ms| 0s | -22ms | -101.695
| | P99| 50ms| 0s | -50ms | -101.010
| deletePost | Avg| 77ms| 64ms | -13ms | -16.919
| | P99| 440ms| 244ms | -196ms | -44.546
| followThreadByUser | Avg| 33ms| 65ms | 32ms | 96.148
| | P99| 214ms| 425ms | 211ms | 98.598
| getAllTeams | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 96ms| 96ms | 0s | 0.000
| getAnalytics | Avg| 167ms| 30ms | -137ms | -82.033
| | P99| 490ms| 98ms | -392ms | -79.997
| getCategoriesForTeamForUser | Avg| 44ms| 44ms | 0s | 0.000
| | P99| 233ms| 234ms | 1ms | 0.429
| getChannel | Avg| 25ms| 18ms | -7ms | -28.545
| | P99| 264ms| 174ms | -90ms | -34.069
| getChannelMember | Avg| 20ms| 21ms | 1ms | 4.913
| | P99| 223ms| 225ms | 2ms | 0.897
| getChannelMembers | Avg| 20ms| 0s | -20ms | -99.885
| | P99| 49ms| 0s | -49ms | -99.155
| getChannelMembersForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 99ms| 102ms | 3ms | 3.035
| getChannelMembersForUser | Avg| 13ms| 11ms | -2ms | -14.944
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 97ms| 103ms | 6ms | 6.175
| getChannelUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 104ms| 98ms | -6ms | -5.753
| getChannelsForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 117ms| 121ms | 4ms | 3.424
| getChannelsForUser | Avg| 12ms| 11ms | -1ms | -8.532
| | P99| 99ms| 95ms | -4ms | -4.021
| getClientConfig | Avg| 18ms| 19ms | 1ms | 5.634
| | P99| 221ms| 225ms | 4ms | 1.812
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 0s | -3ms | -100.515
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 59ms| 60ms | 1ms | 1.695
| | P99| 248ms| 275ms | 27ms | 10.871
| getFileThumbnail | Avg| 49ms| 50ms | 1ms | 2.052
| | P99| 241ms| 245ms | 4ms | 1.657
| getFilteredUsersStats | Avg| 24ms| 0s | -24ms | -98.625
| | P99| 50ms| 0s | -50ms | -100.979
| getGroups | Avg| 36ms| 0s | -36ms | -98.792
| | P99| 99ms| 0s | -99ms | -100.000
| getLicenseSelfServeStatus | Avg| 105ms| 0s | -105ms | -99.789
| | P99| 248ms| 0s | -248ms | -99.799
| getPostThread | Avg| 53ms| 56ms | 3ms | 5.621
| | P99| 424ms| 427ms | 3ms | 0.707
| getPostsForChannel | Avg| 97ms| 94ms | -3ms | -3.078
| | P99| 932ms| 913ms | -19ms | -2.038
| getPostsForChannelAroundLastUnread | Avg| 47ms| 49ms | 2ms | 4.237
| | P99| 440ms| 448ms | 8ms | 1.817
| getPreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 93ms| 92ms | -1ms | -1.074
| getPrevTrialLicense | Avg| 4ms| 0s | -4ms | -105.020
| | P99| 10ms| 0s | -10ms | -101.523
| getProductNotices | Avg| 11ms| 0s | -11ms | -100.243
| | P99| 25ms| 0s | -25ms | -100.604
| getProfileImage | Avg| 84ms| 81ms | -3ms | -3.577
| | P99| 463ms| 463ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 34ms| 32ms | -2ms | -5.884
| | P99| 214ms| 181ms | -33ms | -15.452
| getRolesByNames | Avg| 9ms| 18ms | 9ms | 96.584
| | P99| 48ms| 25ms | -23ms | -47.423
| getSelfHostedProducts | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.946
| getTeamMember | Avg| 10ms| 11ms | 1ms | 10.243
| | P99| 96ms| 97ms | 1ms | 1.039
| getTeamMembersForUser | Avg| 9ms| 10ms | 1ms | 10.561
| | P99| 98ms| 100ms | 2ms | 2.038
| getTeamStats | Avg| 78ms| 78ms | 0s | 0.000
| | P99| 240ms| 243ms | 3ms | 1.253
| getTeamsForUser | Avg| 7ms| 8ms | 1ms | 13.804
| | P99| 82ms| 87ms | 5ms | 6.093
| getTeamsUnreadForUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 183ms| 189ms | 6ms | 3.283
| getThreadsForUser | Avg| 13ms| 14ms | 1ms | 7.542
| | P99| 127ms| 128ms | 1ms | 0.785
| getUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 212ms| 212ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 2ms | 1ms | 66.805
| | P99| 24ms| 30ms | 6ms | 24.729
| getUsers | Avg| 12ms| 13ms | 1ms | 8.147
| | P99| 193ms| 204ms | 11ms | 5.696
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 37ms| 38ms | 1ms | 2.736
| getUsersByNames | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 102ms| 111ms | 9ms | 8.817
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 162ms| 163ms | 1ms | 0.619
| | P99| 1.225s| 1.085s | -140ms | -11.429
| logout | Avg| 153ms| 181ms | 28ms | 18.291
| | P99| 482ms| 860ms | 378ms | 78.423
| patchPost | Avg| 110ms| 108ms | -2ms | -1.811
| | P99| 945ms| 769ms | -176ms | -18.624
| removeUserCustomStatus | Avg| 315ms| 286ms | -29ms | -9.201
| | P99| 996ms| 954ms | -42ms | -4.215
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 35ms| 36ms | 1ms | 2.887
| | P99| 242ms| 247ms | 5ms | 2.063
| searchAllChannels | Avg| 60ms| 58ms | -2ms | -3.347
| | P99| 237ms| 233ms | -4ms | -1.691
| searchGroupChannels | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 150ms| 151ms | 1ms | 0.668
| searchPostsInTeam | Avg| 323ms| 273ms | -50ms | -15.489
| | P99| 2.426s| 2.417s | -9ms | -0.371
| searchUsers | Avg| 55ms| 56ms | 1ms | 1.819
| | P99| 232ms| 236ms | 4ms | 1.722
| setPostReminder | Avg| 52ms| 70ms | 18ms | 34.921
| | P99| 237ms| 457ms | 220ms | 92.729
| unfollowThreadByUser | Avg| 57ms| 64ms | 7ms | 12.376
| | P99| 447ms| 424ms | -23ms | -5.144
| updateCategoriesForTeamForUser | Avg| 227ms| 207ms | -20ms | -8.814
| | P99| 2.103s| 917ms | -1.186s | -56.409
| updatePreferences | Avg| 33ms| 36ms | 3ms | 9.036
| | P99| 248ms| 297ms | 49ms | 19.788
| updateReadStateAllThreadsByUser | Avg| 11ms| 9ms | -2ms | -18.282
| | P99| 25ms| 49ms | 24ms | 97.461
| updateReadStateThreadByUser | Avg| 126ms| 132ms | 6ms | 4.781
| | P99| 776ms| 827ms | 51ms | 6.573
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 433ms| 437ms | 4ms | 0.923
| | P99| 1.852s| 1.871s | 19ms | 1.026
| upsertDraft | Avg| 13ms| 8ms | -5ms | -37.590
| | P99| 25ms| 25ms | 0s | 0.000
| viewChannel | Avg| 39ms| 40ms | 1ms | 2.570
| | P99| 369ms| 387ms | 18ms | 4.875
